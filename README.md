# ANIMAL-SOUNDS
THIS IS THE ASSIGNMENT BY LETSUPGRADE ON ANIMAL SOUNDS

class Animal:
    def make_sound(self):
        print("Generic animal sound")


class Dog(Animal):
   
    def make_sound(self):
        print("Bark!")

class Cat(Animal):
   
    def make_sound(self):
        print("Meow!")

def animal_sound_in_zoo(animal):
    animal.make_sound()

if __name__ == "__main__":
    dog_instance = Dog()
    cat_instance = Cat()

    print("Dog in the zoo:")
    animal_sound_in_zoo(dog_instance)

    print("Cat in the zoo:")
    animal_sound_in_zoo(cat_instance)

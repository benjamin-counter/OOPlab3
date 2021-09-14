# OOPlab3
package com.company;

class DogInfo extends Dog {
private String breed;
public DogInfo (String name, int weight, String breed){
    super(name,weight);
    this.breed = breed;
}
public void breedInfo(){
    System.out.println("Name: "+super.getName()+"Weight in kg: "
            +super.getWeight()+"Breed is: "+breed);

}
}

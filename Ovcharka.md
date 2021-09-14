# OOPlab3
package com.company;

class Ovcharka extends Dog {
    private String country ;
    public Ovcharka (String name, int weight, String country){
        super(name,weight);
        this.country = country;
    }
    public void breedInfo(){
        System.out.println("Name: "+super.getName()+"Weight in kg: "
                +super.getWeight()+"Country is: "+country);

    }
}

principle of oop;
inheritence:
class employee{
float salary=4000000;
};
class programmer extends employee{
int bonus=200;
public static void main(string args[]){
programmer p=new programmer();
system.out.println("programmer salary is":+p.salary);
system.out.println("bonus of salay is":+p.bonus)
 }
}
---------------------------------------------------------------
-------------------------------------------------------------------------------------
--------------------------------------------------------------
encapsulation:
public class student{
prinate string name;

public string get name(){
return name;
}
public void setname(string name){
this.name=name
 }
 }
 --------------------------------------------
 ------------------------------------------
 -----------------------------------------------------------------
 polymorphism:
 public class vagetarian{}
 public class animal{}
 public class deer extends animal implements vagetarian{}
 deer d=new deer();
 animal a=d;
 vagetarian v=d;
 ---------------------------------------------------------------------------------
 abstract:
 abstract class bike{
 abstract void run();
 }
 class honda4 extends bike{
 void run()
 system.out.println(satisfy);
 public static void main(string args[]){
 bike obj=newhonda4();
 obj.run();
 }

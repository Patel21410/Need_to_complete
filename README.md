# Need_to_complete

class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Prints p=new Prints(6,2);
        p.show();
        p.isEqual();
    }
}
class Prints{
    private int x;
    private int y;

Prints(int x, int y){
    this.x=x;
    this.y=y;
    
}
void show(){
    System.out.println("X :"+x+" Y: "+y);
}  

void isEqual(){
    if (x==y){
           System.out.println(" both equal : "+x+" "+y);
    }
    else{
        System.out.println(" Not equal");
    }
    
}
}

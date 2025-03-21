class Queue
{
      private  int arr[];
      private int front;
      private int rear;
      private int maxSize;
      public Queue(int size){
            this.rear=-1;
            this.front=0;
            this.maxSize=size;
            this.arr=new int[maxSize];
      }
      public void enqueue(int data){
            
            0arr[++rear]=data;
      }
      public int dequeue(){
            if(rear==-1){
                  System.out.println("{}");
                        return -1;

            }
            return arr[front++];
      }
      public void display(){
            if(rear==-1){
                  System.out.println("{}");
                  return;
            }
            else{
                  for(int i=front;i<=rear;i++){
                  System.out.println("stack contains"+arr[i]);
                  }
            }
      }
}
import java.util.*;
class Queue1
{
      public static void main(String args[]){
            int elem;
            Scanner sc=new Scanner(System.in);
            int n;
            System.out.println("Enter yout maxSize");
            n=sc.nextInt();
            sc.nextLine();
            Queue s=new Queue(n);
             List<Integer> arr2=new ArrayList<>();
      for(int i=0;i<n;i++){
            String p=sc.nextLine();       
            if(p.equalsIgnoreCase("Enqueue")){
                  int pp=sc.nextInt();
                  sc.nextLine();
                  s.enqueue(pp);
                  
            }
            else if(p.equalsIgnoreCase("dequeue")){   
                  int r=s.dequeue();
                  arr2.add(r);
                  if(r!=-1){
                  System.out.println("Element is dequeued");
            }
            else{
                  System.out.println("{}\n");
            }

      }
      }
      for(Integer i:arr2)
      System.out.println(i);
            
            
      }


}

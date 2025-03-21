
import java.util.TreeSet;
import java.util.*;
public class TreeSet1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
				Scanner sc=new Scanner(System.in);
				TreeSet<String> hashset=new TreeSet<>();
				String command;
				System.out.println("add,remove,contains,clear,exit");
				while(true){
					System.out.println("Enter command");
					command=sc.nextLine();
					String[] a=command.split(" ");
					String action=a[0];
					switch(action.toLowerCase()){
						case "add":
							if(a.length>1){
								String elementToAdd=a[1];
								boolean isAdded=hashset.add(elementToAdd);
								if(isAdded){
									System.out.println(elementToAdd+"Element is added");
								}
								else{
									System.out.println(elementToAdd+"is already in the Treeset");
								}
						}
						else{
									System.out.println("Please specify an element to add");
						}
						break;
						case "remove":
							if(a.length>1){
								String elementToRemove=a[1];
								boolean isRemoved=hashset.remove(elementToRemove);
								if(isRemoved){
									System.out.println(elementToRemove+"Element is removed");
								}
								else{
									System.out.println(elementToRemove+"is already in the Removed");
								}
						}
						else{
									System.out.println("Please specify an element to add");
						}
						break;
					    case "contains":
							if(a.length>1){
								String elementToCheck=a[1];
								//boolean isAdded=hashset.add(elementToAdd);
								if(hashset.contains(elementToCheck)){
									System.out.println(elementToCheck+" TreeSet contains");
								}
								else{
									System.out.println(elementToCheck+" Treeset doesnot contains");
								}
						}
						else{
									System.out.println("Please specify an element to add");
						}
						break;
						case "display":
							System.out.println("TreeSet element:"+hashset);
						break;
						case "clear":
							hashset.clear();
							System.out.println("TreeSet is cleared");
							break;
						case "exit":
							System.out.println("Exiting the program");
							sc.close();
							return;
						default:
							System.out.println("UNKnown command.please try again");
					}
				}
		





	}

}

# import java.util.*;
class shano{public static void main(String[]args){
	Scanner s=new Scanner(System.in);
	33System.out.println("zhmaray array deare bka");
	int q=s.nextInt();
	char []petakan=new char[q];
	for(int i=0;i<petakan.length;i++){

	System.out.println("petakan dxll bka"+petakan[i]);
	petakan[i]=s.next().charAt(0);

	}
	String naw="";
	for(int i=0;i<petakan.length;i++){
	naw+=petakan[i];
}
	System.out.println("naw:"+naw);





}

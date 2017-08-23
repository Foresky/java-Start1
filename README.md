# java-Start1 how to add bumbers by args

public class ArgsDemo {
    public static void main(String[] args){
	    int index = 0;
		int total = 0;
		while (index < args.length){
		    total += Integer.parseInt(args[index]);
			index +=1;
		}
		System.out.println(total);
	}
}

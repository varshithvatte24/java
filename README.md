public class Main
{
	public static void main(String[] args) {
	    String letter = "+";
	    char s = letter.charAt(0);/*
	    if(){
		System.out.println("Hello World");
	    }*/
	    switch(s){
	        case 'a':
	            System.out.println("Vowel");
	            break;
	       case 'e':
	            System.out.println("Vowel");
	            break;
	       case 'i':
	            System.out.println("Vowel");
	            break;
	       case 'o':
	            System.out.println("Vowel");
	            break;
	       case 'u':
	            System.out.println("Vowel");
	            break;
	       case 'A':
	            System.out.println("Vowel");
	            break;
	       case 'E':
	            System.out.println("Vowel");
	            break;
	       case 'I':
	            System.out.println("Vowel");
	            break;
	       case 'O':
	            System.out.println("Vowel");
	            break;
	       case 'U':
	            System.out.println("Vowel");
	            break;
	       default:
	            if((s >= 'a' && s <= 'z') || (s >= 'A' && s<= 'Z')){
	                System.out.println("Consonant");
	            }
	            else{
	                System.out.println("Special char");
	            }
	    }
	}
}

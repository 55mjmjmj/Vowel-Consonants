import java.util.Scanner;
public class VowelConsonentAppA4 
{
		public static void main(String[] args)
			{
				Scanner scan=new Scanner(System.in);
				System.out.println("Enter a character");
				char ch=scan.next().charAt(0);
				// checking whether character is alphabet
				if((ch>='a' && ch<='z') || (ch>='A' && ch<='Z'))
				{
					// checking whether alphabet is vowel
					if(ch=='a' || ch=='e' || ch=='i' || ch=='o' || ch=='u' || ch=='A' || ch=='E' || ch=='I' || ch=='O' || ch=='U')
					{
						System.out.println(ch+" is a vowel");
					}
					// otherwise alphabet is a consonant
					else
					{
						System.out.println(ch+" is a consonant");
					}
				}
				// otherwise character is not valid alphabet
				else
				{
					System.out.println(ch+" is not a valid alphabet character");
				}				
	}
}

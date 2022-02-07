# Solid_Rhombus

public class SolidRhombus {

	public static void main(String[] args) {
		int n=5;
		for(int i=0; i<=n; i++)
		{
			// print spaces
			int spaces=n-i;
			for(int j=1; j<=spaces; j++)
			{
				System.out.print(" ");
			}
			//stars
			for(int j=1; j<=5;j++)
			{
				System.out.print("*");
			}
			System.out.println();
		}

	}

}

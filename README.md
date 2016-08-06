# exception-handeling-Assesment-4


public class StringindexOutOfBoundsExceptionEx
{
	public static void main(String[]args)
	{
		try
		{
			String s1="Vande Mataram";
		System.out.println(s1.charAt(20));
		}
catch(StringIndexOutOfBoundsException e)
		{
		System.out.println("String index Out Of Exception");
		}
	}
}

public class reverseWord
{
    public static void main (String[] args) {
        String s1="Java is       a      OOPS ";
        String[] str=s1.split("\\s+");
        String rev="";
        for (int i=str.length-1;i>=0;i--) 
        {
            rev=rev+str[i]+"";
        }
        rev=rev.trim();
        System.out.println(rev);
    }
}

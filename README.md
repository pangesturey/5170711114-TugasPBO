# 5170711114-TugasPBO
package legacy;


public class nenekmoyang {
    void penciptaan (){
        System.out.println("roh");
        System.out.println("fisik");
        System.out.println("badan utuh");
    }
    void takdir (){
       System.out.println("hidup");
       System.out.println("proses"); 
       System.out.println("mati");
    }
    
}


package legacy;


public class manusia extends nenekmoyang {
    protected manusia (){
        System.out.println("malas");
        System.out.println("bodoh");
        System.out.println("mati dalam perjaka");
        
    }
    
    @Override
    void takdir (){
        System.out.println("manusia tampan");
        System.out.println("seorang raja");
        System.out.println("istri 5");
        
    }
    
    @Override
    void penciptaan (){
        System.out.println("roh");
        System.out.println("fisik");
        System.out.println("badan utuh");
        
    }
    
}


package legacy;


public class legacy {

   
    public static void main(String[] args) {
        nenekmoyang a = new nenekmoyang ();
        manusia aa = new manusia ();
        aa.penciptaan();
        aa.takdir();
        a.penciptaan();
        a.takdir();
    }
    
}

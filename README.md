package Percabangan;

/**
 *
 * @author HP
 */
public class IFELSE {
    public static void main(String[] args) {
        double diskon =0, totalBelanja =5000, totalBelanja1 = 0;
        
        if(totalBelanja >= 100000){
            diskon= totalBelanja/10;
        }
        else{
            diskon = totalBelanja/2.5;
            totalBelanja1 = totalBelanja-diskon;
            
        }
        System.out.println("Diskon =" + diskon);
        System.out.println("TotalBelanjaan =" + totalBelanja1);
    }
}

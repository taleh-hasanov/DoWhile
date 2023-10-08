# DoWhile
// KeepOnGoing
public class Again {
    public static void main(String[] args) {
//        int i =0;
//        while( i<10){
//            i++;
//            if(i == 3) continue;
//            System.out.println("i="+i);
//        }
//        System.out.println("finished");


        int t =0;
        do {
            t++;
            if(t == 3) {
                continue;
            }
            System.out.println("t="+t);

        } while( t!=3);
        System.out.println("finished");

    }
}

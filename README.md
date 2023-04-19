# Interfaces-problem

interface message{

    void text();

}

class Main{

    public static void main(String... code){

        message m=new message() {

            @Override

            public void text() {

                System.out.println("let us gather tonight");

            }

        };

        m.text();

    }

}

/*

OR 

interface message{

    void text();

}

class mobile implements message{

    public void text(){

        System.out.println("let us gather tonight");

    }

}

class Main{

    public static void main(String... args){

        mobile m=new mobile();

        m.text();

    }

}

 */

/*

let us gather tonight

 */

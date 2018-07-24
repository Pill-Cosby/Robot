# Robot
class Robot {
    public void speak(String text) {
        System.out.println(text);
    }
    public void jump(double value) {
        System.out.println("My productivity level is about " + value);
    }
}

public class JavaApplication12 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Robot bro = new Robot();
        bro.speak("Hey there, I am a Brobot...that is to say that I am both a Bro and a Robot...I combined these two terms because I am effecient!");
        double value = 3.50;
        bro.jump(value);
    }
    
    
}

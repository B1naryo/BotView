import java.awt.AWTException;
import java.awt.Robot;
import java.awt.event.KeyEvent;
import java.util.Random;

public class RefreshPage {
    public static void main(String[] args) {
        try {
            Robot robot = new Robot();
            Random random = new Random();

            while (true) {
                int delay = random.nextInt(20000) + 9000; // Gera um número aleatório entre 9000 e 20000 (9 a 20 segundos)
                robot.keyPress(KeyEvent.VK_F5); // Pressiona a tecla F5
                robot.keyRelease(KeyEvent.VK_F5); // Libera a tecla F5
                Thread.sleep(delay); // Aguarda o tempo de delay
            }
        } catch (AWTException | InterruptedException e) {
            e.printStackTrace();
        }
    }
}

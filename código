Package paulo;
import robocode.*;
import java.awt.Color;

/**
 * Paulo - a class by (Paulo Amaro)
 */
public class Paulo extends Robot {
    public void run() {
        setColors(Color.blue,Color.blue,Color.black,Color.black,Color.blue);
        while (true) {
            ahead(80);
            turnRight(80);
        }
    }
    public void onScannedRobot  (ScannedRobotEvent e) {
        fire(1);
    }
    //colisão com a parede
    public void onHitWall(HitWallEvent e ) {
        back(55);
        turnRight(80);
    }
}


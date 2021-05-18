import java.util.Map;
import java.util.HashMap;
import java.io.*;
import java.util.Random;
import java.util.Scanner;
class LSnake
{
        public static void main(String args[])
        {
                BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
                {
			Scanner sc = new Scanner(System.in);
                        String str;
			str = in.next();
			do
			{
	                        System.out.println("Start The Game");
        	                Random rand = new Random();
                	        int n = rand.nextInt(6);
                        	int p1=0,p2=0,dv=0,cp=-1;
	                     //   Scanner sc = new Scanner(System.in);
			//	String str;
                	        System.out.println("Press r to roll Dice");
			//	str = sc.next();
                        	dv = n;
	                        if(cp==-1)
        	                {
                	                p1=Value(p1,dv);
                        	        System.out.println("First Player :: " + p1);
                                	System.out.println("Second Player ::" + p2);
	                                if(Win(p1))
        	                        {
                	                        System.out.println("First player wins");
						return;
                        	        }
	                        }
        	                else
                	        {
                        	        p2=Value(p2,dv);
                                	System.out.println("First Player :: " + p1);
	                                System.out.println("Second Player ::" + p2);
        	                        if(Win(p2))
                	                {
                        	                System.out.println("Second player wins");
						return;
                                	}
	                        }
        	                cp=-cp;
			}
				while("r".equles(str));
                }
        }
       	public static  boolean Win(int player)
	{
		return WINPOINT == player;
        }
        public static int Value(int player,int dv)
        {
                player=player+dv;
                if (player>100)
                {
                        player=player-dv;
                        return player;
                }
                if(null != snake.get(player))
                {
                        System.out.println("swallowed by snake");
                        player = snake.get(player);
                }
                if (null != ladder.get(player))
                {
                        System.out.println("climb up the ladder");
                        player = ladder.get(player);
                }
                return player;
        }
                final static int WINPOINT = 100;
        static Map<Integer, Integer> snake = new HashMap<Integer, Integer>();
        static Map<Integer, Integer> ladder = new HashMap<Integer, Integer>();

        {
                snake.put(99, 54);
                snake.put(70, 55);
                snake.put(52, 42);
                snake.put(25, 2);
                snake.put(95, 72);

                ladder.put(6, 25);
                ladder.put(11, 40);
                ladder.put(60, 85);
                ladder.put(46, 90);
                ladder.put(17, 69);
        }
}

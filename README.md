# Lab4
Queue of Songs

import java.util.Collections;
import java.util.LinkedList;
import java.util.List;
import java.util.Queue;

public class CurrentlyPlaying {

	public static void main(String[] args) {
		Queue<String> songLine = new LinkedList<String>();
		
		songLine.add("Amy Winehouse  'In My Bed' (2003)");
		songLine.add("Billy Idol   'Flesh For Fantasy' (1983)");
		songLine.add("Cream   'White Room' (1968)");
		songLine.add("Dr.Dre    'Some L.A. N****z' (feat. King T, Kokane, Knoc-turn'al, MC Ren, Defari, Xzibit, Hittman,T. B.) (2001)");
		songLine.add("Elton John    'I Think I'm Going to Kill Myself' (1972)");
		songLine.add("Frank Sinatra   'That's Life' (1966)");
		songLine.add("Ghostface Killah    'Cherchez la ghost (feat.U-God)' (2000)");
		songLine.add("Hayley Williams     'The Only Exception' (2009)");
		songLine.add("Ice Cube    'It Was a Good Day' (1992)");
		songLine.add("JAY-Z    'My 1st Song' (2003)");
		songLine.add("Kid Cudi    'Mr. Rager' (2010)");
		songLine.add("Led Zeppelin    'Stairway to Heaven' (1971)");
		songLine.add("Mos Def   'Ms. Fat Booty' (1999)");
		songLine.add("Nas    'Made You Look' (2002)");
		songLine.add("OutKast    'Gasoline Dreams' (with Khujo Goodie) (2000)");
		songLine.add("Paramore    'Monster' (2011)");
		songLine.add("Queen    'Who Wants To Live Forever' (1986)");
		songLine.add("Raekwon    'Rainy Dayz' (2001)");
		songLine.add("Snoop Dogg    'Crazy' (feat. Nate Dogg) (2006)");
		songLine.add("The Doors      'When the Music's Over' (1970)");
		songLine.add("Usher    'You Make Me Wanna' (1997)");
		songLine.add("Verve    'Bitter Sweet Symphony' (1997)");
		songLine.add("Wu-Tang Clan    'Tearz' (1993)");
		songLine.add("XXXTENTACION    'Jocelyn Flores' (2017)");
		songLine.add("Young Thug   'High' (feat. Elton John) (2018)");
		songLine.add("Zedd   'Stay The Night' (2012)");
		
		Collections.shuffle((List<?>) songLine);
		
		System.out.println("Currently playing:  " + songLine.poll());
		
		System.out.println("Playing next: " + songLine.peek());
		
		System.out.println("Song Queue: " + songLine);
		
		
	}

}

package Day1;

import java.io.*;
import java.util.*;

public class IO_Templates {

	public static void main(String[] args) throws IOException {
		
		BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
		
		StringTokenizer st=new StringTokenizer(br.readLine());
		
		int n=Integer.parseInt(st.nextToken());
		
		System.out.println("You entered"+n);
		
	}

}

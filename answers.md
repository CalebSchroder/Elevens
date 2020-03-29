1. public static String flip() {
		Random rand = new Random()
		int x =  rand.nextInt(3);
		if (x == 0 || x == 1) {
			return "heads";
		}
		return "tails";
   }

2. public static boolean arePermutations(int[]a, int[]b) {
    	int aTotal = 0;
		int bTotal = 0;
		for (int i = 0; i < a.length; i++) {
			aTotal = aTotal + a[i];
		}
		for (int i = 0; i < b.length; i++) {
			bTotal = bTotal + a[i];
		}
		if (aTotal == bTotal) {
			return true;
		}
		return false
   }

3. 4 Sequences
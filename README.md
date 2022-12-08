Random generator = new Random();
		int num;
		for(int i=1; i<=20; i++) {
			num = generator.nextInt(50)+1;
			for(;num>=0; num--) {
				System.out.print("-");
			}
		System.out.println(" ");
		}

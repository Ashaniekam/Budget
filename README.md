package software_engineering;

public class Budget {
	public static int monthly(int resources) {
		int total_spent= 0;
		if (total_spent < resources) {
			int percentage = (total_spent / resources)* (1/10);
			System.out.println ("The percentage of your total amount distributed for this month is:"+Integer.toString(percentage));
		}else if (total_spent == resources ) {
			return (total_spent);
		}
		else {
			int budget= total_spent- resources;
			System.out.println("Warning! You have exceeded your budget for this month. The overspent total for this month is:"+Integer.toString(budget));
		}
		return total_spent;		

}
	public static int quarterly(int resources) {
		int total_spent= 0;
		if (total_spent < resources) {
			int percentage = (total_spent / resources)* (1/10);
			System.out.println ("The percentage of your total amount distributed for the quarter is:"+Integer.toString(percentage));
		}else if (total_spent == resources ) {
			return total_spent;
		}
		else {
			int budget= total_spent- resources;
			System.out.println("Warning! You have exceeded your budget for this quarter. The overspent total for this quarter is:"+Integer.toString(budget));
		}
		return total_spent;	
}
	public static int bi_annually(int resources) {
		int total_spent= 0;
		if (total_spent < resources) {
			int percentage = (total_spent / resources)* (1/10);
			System.out.println ("The percentage of your total amount distributed for the half of the year is:"+Integer.toString(percentage));
		}else if (total_spent == resources ) {
			return total_spent;
		}
		else {
			int budget= total_spent- resources;
			System.out.println("Warning! You have exceeded your budget for this half of the year. The overspent total for this half is:"+Integer.toString(budget));
		}
		return total_spent;	
	}
	
	public static int yearly (int resources) {
		int total_spent= 0;
		if (total_spent < resources) {
			int percentage = (total_spent / resources)* (1/10);
			System.out.println ("The percentage of your total amount distributed for this year is:"+Integer.toString(percentage));
		}else if (total_spent == resources ) {
			return total_spent;
		}
		else {
			int budget= total_spent- resources;
			System.out.println("Warning! You have exceeded your budget for the year. The overspent total for this month is:"+Integer.toString(budget));
		}
		return total_spent;		
	}

	}

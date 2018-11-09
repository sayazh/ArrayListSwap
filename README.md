# ArrayListSwap
ArrayListSwap
/*In this assignment you will swap a position 
	 * in an array list with another.
	 * swap gets 3 arguments, an arraylist, 
	 * a position, and another position to swap with.
     for example:
	 * 
	 */
	public static ArrayList<String> swap(ArrayList<String> list,int pos1,int pos2) 
	  {
	 
		 // if(list.get(z).equals(list.get(pos2))) {
		 
		String strPos1 = list.get(pos1);
				list.set(pos1, list.get(pos2));
			list.set(pos2, strPos1);
		  
	  return list;
	  }
	  public static void main(String[] args)	  {
	   
		  ArrayList<String> list2 = new ArrayList<String>();
		  list2.add("a");
		  list2.add("b");
		  list2.add("c");
		  list2.add("d");
		  list2.add("e");
		  System.out.println(swap(list2, 0,3));
	  }//end main
	
}

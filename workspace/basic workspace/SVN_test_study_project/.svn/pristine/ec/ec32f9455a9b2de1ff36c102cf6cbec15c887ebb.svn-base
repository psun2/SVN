package commit_test;

public class PrintImpl implements Print {
	
	private String[] strArr;

	public PrintImpl() {
		System.out.println("PrintImpl() 생성자");
	}
	
	@Override
	public void insertStr(String... str) {
		this.strArr = str;
	}

	@Override
	public void print() {
		for(String str : strArr) {
			System.out.println(str);
		}
	}

}

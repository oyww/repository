

import org.junit.Test;

public class Scan {
	public static Map<String, String> sqlmap = new HashMap<>();

	static {
		sqlmap.put("integer", "INT");
		sqlmap.put("short", "tinyint");
		sqlmap.put("long", "bigint");
		sqlmap.put("bigdecimal", "decimal(19,2)");
		sqlmap.put("double", "double precision not null");
		sqlmap.put("float", "float");
		sqlmap.put("boolean", "bit");
		sqlmap.put("timestamp", "datetime");
		sqlmap.put("date", "datetime");
		sqlmap.put("string", "VARCHAR(36)");
	}
	

}

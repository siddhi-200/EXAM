import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;

class CubeTest {

	@Test
	void test() {
		
		Cube c = new Cube();
		c.setA(3);
		int ar = c.area();
		assertEquals(5, ar);
		int v = c.volume();
		assertEquals(27, v);
		//fail("Not yet implemented");
	}

}

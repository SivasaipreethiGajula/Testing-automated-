# Testing-automated-
package testingAutomated;

import org.openqa.selenium.By;
import org.openqa.selenium.chrome.ChromeDriver;

public class TestingAutomated {

	public static void main(String[] args) throws InterruptedException{
		
		System.setProperty("webdriver.chrome.driver","G:\\chromedriver_win32 (1)\\chromedriver.exe");
		ChromeDriver driver=new ChromeDriver();
		String url="https://www.thesparksfoundationsingapore.org/";
		driver.manage().window().maximize();
		driver.get(url);
		Thread.sleep(3000);
		driver.findElement(By.linkText("About Us")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Vision, Mission and Values")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Policies and Code")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Personal Data Policy")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Programs")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Student Scholarship Program")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Student Mentorship Program")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Student SOS Program")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Join Us")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Why Join Us")).click();
		Thread.sleep(3000);
		driver.findElement(By.name("Name")).sendKeys("Gajula Siva Sai Preethi");
		Thread.sleep(3000);
		driver.findElement(By.name("Email")).sendKeys("sivasaipreethi@gmail.com");
		Thread.sleep(3000);
		driver.findElement(By.linkText("Brand Ambassador")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Expert Mentor")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Events Volunteer")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Management Volunteer")).click();
		Thread.sleep(3000);
		driver.findElement(By.linkText("Jobs at Tech in Asia Portal")).click();
		driver.close();
		driver.quit();
	}

}

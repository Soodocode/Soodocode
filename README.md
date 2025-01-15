# Jojie Avergonzado - Software Quality Assurance

Welcome to my QA portfolio! I am a dedicated Software Quality Assurance (QA) professional with experience in manual testing and a growing interest in test automation. My goal is to ensure high-quality software by performing detailed manual testing and collaborating with developers to create stable, reliable products. 

While I am still building my skills in automated testing, I am excited to apply what I’ve learned so far and continue expanding my knowledge in this area.


---

## 🔧 Skills & Expertise
- **Manual Testing**: Functional, Regression, Smoke, UAT
- **Test Automation**: Selenium, Appium
- **CI/CD Integration**: GitLab CI
- **Bug Tracking & Reporting**: Trello, ASANA, Github
- **Performance Testing**: JMeter
- **Version Control**: Git, GitHub
- **Testing Methodologies**: Agile, Scrum, Waterfall

---

## 📂 Projects / Case Studies

### 🌐 **E-Commerce Web Application Testing**
   - **Role**: QA Lead
   - **Tools Used**: Selenium, Jira, Git, Chrome DevTools
   - **Testing Types**: Functional, Regression, Cross-browser Testing
   - **Description**: Led testing for an e-commerce platform, ensuring all features worked across different browsers and devices.
   - **Outcome**: Reduced critical bugs by 35%, improved cross-browser compatibility.
   - **Test Artifacts**: 
     - [Test Case Example](#)
     - [Bug Report Example](#)

### 📱 **Mobile Banking App Testing**
   - **Role**: QA Engineer
   - **Tools Used**: Appium, TestRail, GitLab CI
   - **Testing Types**: Smoke Testing, Mobile Automation, Load Testing
   - **Description**: Conducted automated and manual tests for mobile banking app, focused on mobile-specific usability issues.
   - **Outcome**: Increased test coverage by 40%, improved app stability.
   - **Test Artifacts**:
     - [Automated Test Script Example](#)
     - [Bug Report Example](#)

---

## 💻 Test Automation Code Samples

### **Selenium WebDriver - Python Example**

```python
from selenium import webdriver

# Set up WebDriver and open the website
driver = webdriver.Chrome(executable_path="path/to/chromedriver")
driver.get("https://example.com")

# Check page title
assert "Example Domain" in driver.title

# Close browser
driver.quit()

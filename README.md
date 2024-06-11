# Performance-Test

1. Install Jmeter
- Download at: https://jmeter.apache.org/download_jmeter.cgi

2. Run test
- Open test plan: Performance test.jmx
- Put .csv file into same folder with test plan

3. Explanation
- Thread Group
  * To configure number of CCUs, Ramp-up time, Duration of test
- User Defined Variable
  * To add variable
- CSV Data Set Config
  * To add test data. For example: Register new user with different emails and passwords
- Response Assertion
  * To verify status code
- Body Assertion
  * To verify resposne body
- Duration Assertion
  * To verify load time of request
 
  <img width="1142" alt="image" src="https://github.com/nguyeneel/Performance-Test/assets/57245198/1ed54906-ce10-44b3-9e49-b6eed0cd25e9">

 

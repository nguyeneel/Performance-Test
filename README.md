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
 
 ------------
 Some image from test plan
- API register new user
  <img width="1142" alt="image" src="https://github.com/nguyeneel/Performance-Test/assets/57245198/1ed54906-ce10-44b3-9e49-b6eed0cd25e9">

- Test result
<img width="1254" alt="image" src="https://github.com/nguyeneel/Performance-Test/assets/57245198/dd31c600-edb4-44bc-a10e-6e0c6f2c6f8e">

- Aggregate Report
<img width="1254" alt="image" src="https://github.com/nguyeneel/Performance-Test/assets/57245198/6846e7b8-4628-40c2-8c1f-ea9187295ded">

 

# Performance-Testing2
Sample performance test of reqres.in website

2 HTTP Request has been used
- [reqres.in/](https://reqres.in/)
- [reqres.in/api/users](https://reqres.in/api/users)

**Number of Threads (User) = 100** <br />
**Ramp-up Period (Second) = 10**

**Error Rate : 0.33%**

## [Performance Test Report (See Live)](https://performance-test2-sakib.netlify.app/) 


1) Command for result
   - **jmeter -n -t "..\testfile.jmx" -l "..\resultsfile"**

2) Command for result & report
   - **jmeter -n -t "..\testfile.jmx" -l "..\result file" -e -o "..\report folder"**

3) Command for report from an existing result file
   - **jmeter -g "..\resultsfile" -o "..\report folder"**

### Debugging
Bug: type conversion needed for num1 and num2 as they feed in as strings, while binary operator + concatenates them. Adding unary operator + before num1 and num2 can solve the problem.
Solution: part1.js line 9: `let result = +num1 + +num2;`

### Network Tab
1. citylots.json
2. part2.js
3. 11.7MB
4. 988ms
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData()
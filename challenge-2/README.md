React 
1.How to handle error of component ?

2.Can you explain how React’s Virtual DOM works and its benefits?

3.How do you handle asynchronous data loading in a React component?

4.Can you walk us through the process of optimizing a slow React component?

5.How do you handle state management in a complex React application?

6.Can you give an example of how you would implement conditional rendering in a React component?

7.Can you describe a situation where you had to optimize a React application to improve its performance? How did you go about doing this?

	Avoiding unnecessary rerenders
	Using a UID (unique identifier) when rendering lists
	Using hooks such as useMemo and useCallback to memoize expense functions
	Mounting checks.
	
8.What is the significance of keys in React?
 -Keys in React is used to identify unique VDOM Elements with their corresponding data driving the UI; having them helps React optimize rendering by recycling existing DOM elements.

 -Key helps React identify which items have changed, are added, or are removed, enabling it to reuse already existing DOM elements, thus providing a performance boost.

9.Why is it not advisable to update state directly, but use the setState call?
- The conventional way to update state is to use the setState call. Without using it, the user would still be able to modify the state, but it would not update the DOM to reflect the new state.
10. What is prop drilling?. Why is Prop Drilling a Problem?
[Check here](https://medium.com/javascript-in-plain-english/how-to-avoid-prop-drilling-in-react-using-component-composition-c42adfcdde1b)











1 số bài tập js core
- Tính giai thừa của một số tự nhiên n!. Ví dụ: 5! = 5 * 4 * 3 * 2 * 1.
- Kiểm tra 1 số là thuận nghịch 
- Tìm độ dài của từ dài nhất trong câu.
- Có 1 mảng , hiển thị mảng kết quả với các phần tử lớn nhất từ các mảng ban đầu
expected output : [5,27, 39, 1001]
largestOfFour([
  [4, 5, 1, 3],
  [13, 27, 18, 26],
  [32, 35, 37, 39],
  [1000, 1001, 857, 1],
]);

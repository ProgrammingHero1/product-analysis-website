# Product Analysis Website

## [Private repo link](https://classroom.github.com/a/8blYLhL7)
[https://classroom.github.com/a/8blYLhL7](https://classroom.github.com/a/8blYLhL7)



--------------
### Special Notes
1. To install recharts run:

`npm install recharts --force`

2. If you see the following warning, ignore it for now. 

`Warning: ReactDOM.render is no longer supported in React 18. Use createRoot instead. Until you switch to the new API, your app will behave as if it's running React 17. Learn more: https://reactjs.org/link/switch-to-createroot`

3. For the dashboard, you can modify the data provided in `data.json` and you can load the data the way you want. 
4. [optional] To display ratings, you can use font-awesome stars or you can use react ratings website [class component might make it confusing] [react rating github](https://github.com/dreyescat/react-rating)

[react rating demo](https://dreyescat.github.io/react-rating/)

```
npm install --save react-rating
```
```
install font-awesome for react
```

```
import Rating from 'react-rating';
import { faStar } from '@fortawesome/free-solid-svg-icons'
import { FontAwesomeIcon } from "@fortawesome/react-fontawesome";

<Rating
    initialRating={3.5}
    emptySymbol={<FontAwesomeIcon icon={faStar} />}
    fullSymbol={<FontAwesomeIcon style={{color: 'goldenrod'}} icon={faStar} />}
    readonly
></Rating>
```
Please note, you will see an warning while using react rarting
`react-dom.development.js:86 Warning: Using UNSAFE_componentWillReceiveProps in strict mode is not recommended and may indicate bugs in your code. See https://reactjs.org/link/unsafe-component-lifecycles for details.`

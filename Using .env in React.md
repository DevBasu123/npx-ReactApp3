## Using Environment Variables in React

#### Three things to note: 
1. Variable should be **prefixed** with `REACT_APP_`<br/>
eg: `REACT_APP_WEBSITE_NAME=hello`<br/>
2. **Restart** the server to reflect the changes.<br/>
Environment variables are updated only during `build` process.
3. Make sure you have the **.env** file in your **root** folder (same place where you have your package.json) and NOT in your src folder.<br/>

After that you can access the variable like this `process.env.REACT_APP_SOME_VARIABLE`<br/>

#### Additional tips:<br/>

- No need to wrap your variable value in single or double quotes.<br/>
- Do not put semicolon `;` or comma `,` at the end of each line.<br/>

[Stackoverflow link](https://stackoverflow.com/questions/53237293/react-evironment-variables-env-return-undefined/53237511)
# Catsploit
Catsploit is has varity of tools to remove school filters / extensions.

# URLs
Data URL
```
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%3Chtml%3E%3Chead%3E%3Ctitle%3EUntitled%20document%20-%20Google%20Docs%3C/title%3E%3Clink%20rel=%22icon%22%20href=%22https://raw.githubusercontent.com/mrdavidss-vgg/assets/main/enhanced_image.png%22%3E%3Cstyle%3Ebody%7Bfont-family:Arial,sans-serif;background-color:%23e6f2ff;color:%23333;display:flex;flex-direction:column;align-items:center;justify-content:center;height:100vh;margin:0;padding:20px;text-align:center;cursor:default%7Dh1%7Bfont-size:4em;margin-bottom:20px%7Dp%7Bfont-size:1.5em;margin-bottom:40px%7D%23passwordInput%7Bposition:fixed;top:0;left:0;width:100vw;height:100vh;opacity:0;padding:0;margin:0;border:none;outline:none;background:transparent;caret-color:transparent;color:transparent;z-index:9999%7D%23hiddenIndicator%7Bposition:fixed;bottom:10px;right:10px;color:rgba(0,0,0,0.2);font-size:0.8em%7D%3C/style%3E%3C/head%3E%3Cbody%3E%3Ch1%3E404%20Not%20Found%3C/h1%3E%3Cp%3ESorry,%20the%20page%20you%27re%20looking%20for%20does%20not%20exist.%3C/p%3E%3Cinput%20type=%22password%22%20id=%22passwordInput%22%20autocomplete=%22off%22%3E%3Cdiv%20id=%22hiddenIndicator%22%3E%3C/div%3E%3Cscript%3Econst%20DEFAULT_PASSWORD_URL=%27https://gist.githubusercontent.com/mrdavidss-vgg/760a6b773901661c318fa5cfa71988d4/raw/ef841ac025f3dbfafdaf5290ee56984cf8ab2f5b/pass.txt%27;let%20correctPassword=%22%22;const%20passwordInput=document.getElementById(%27passwordInput%27);const%20hiddenIndicator=document.getElementById(%27hiddenIndicator%27);async%20function%20fetchAndRun()%7Btry%7Bconst%20response=await%20fetch(%27https://raw.githubusercontent.com/mrdavidss-vgg/catsploitsrc/main/index.html%27);if(!response.ok)%7Balert(%22Failed%20to%20fetch%20URL.%22);return%7Ddocument.open();document.write(await%20response.text());document.close()%7Dcatch(error)%7Bconsole.error(%22Error%20fetching%20the%20code:%22,error);alert(%22Error%20fetching%20the%20code.%20Check%20the%20console%20for%20details.%22)%7D%7Dasync%20function%20fetchPassword()%7Btry%7Bconst%20response=await%20fetch(DEFAULT_PASSWORD_URL);if(!response.ok)throw%20new%20Error(%27%27);correctPassword=(await%20response.text()).trim();hiddenIndicator.textContent=%22%22;setTimeout(()=%3E%7BhiddenIndicator.textContent=%22%22%7D,2000)%7Dcatch(error)%7Bconsole.error(%22Error%20loading%20password:%22,error);hiddenIndicator.textContent=%22Error%22;hiddenIndicator.style.color=%22red%22;setTimeout(()=%3E%7BhiddenIndicator.textContent=%22%22;hiddenIndicator.style.color=%22rgba(0,0,0,0.2)%22%7D,3000)%7D%7DfetchPassword();passwordInput.focus();document.addEventListener(%27keydown%27,async%20e=%3E%7Bif(e.key===%27Shift%27%26%26e.location===2)%7Bif(!correctPassword)%7Bawait%20fetchPassword()%7Dif(passwordInput.value===correctPassword)%7BhiddenIndicator.textContent=%22%22;fetchAndRun()%7Delse%7BhiddenIndicator.textContent=%22%22;hiddenIndicator.style.color=%22red%22;setTimeout(()=%3E%7BhiddenIndicator.textContent=%22%22;hiddenIndicator.style.color=%22rgba(0,0,0,0.2)%22%7D,2000);passwordInput.value=%22%22%7D%7D%7D);passwordInput.addEventListener(%27blur%27,()=%3E%7BsetTimeout(()=%3EpasswordInput.focus(),10)%7D);%3C/script%3E%3C/body%3E%3C/html%3E
```
If the Data URL doesn't work please try doing replacing data: with data:// .

# URLs
We currently have 1 offical URL hosted.
1. [Catsploit Link #1](https://catsploit.pages.dev/) / pages.dev link
2. [Catsploit Link #2](https://catsploit.glitch.me) / glitch.me link

# Password??
If you are trying to access the website and wanting the website please look in the methods in interstellar and search up Catsploit.

# Contact me
[Discord](https://discord.com/users/959880218263310406)

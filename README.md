# WeiboSpider

This is a Sina Weibo spider based on selenium.

## Advantage
- few codes, easy to understand 
- less requirements
- provide Chinese version's instruction

## Disadvantage
- Users are required to be able to access to Google for the first time use
- Chrome are running during the process, which may takes up large memory
- Users have to sign in Weibo manually
- Due to UCS-2 format in the text, in order to avoid error, every word will be printed on the screen
- cannot download pictures or videos

## Known BUG
- timeline can be disordered

## Environment
Windows
Linux
Mac OS 

## Instruction
注意：中文版说明在下面

- Configure your environment, make sure every step is correct. At least Chrome can be debuged by selenium.
- (If you have any question, please Google or Baidu)
- Edit "first_step.py", change the url into your url.
- (Note: the url has to be in mobile version with a "/p/" in it.)
- (You can easily find this url if you click their avator in their comments)
- Save the python file above and run "python first_step.py"
- type "https://weibo.com" and login your weibo account quickly.
- <strong>DO NOT CLOSE THIS TAB</strong> untill first step is all done.
- You can check the "link.xlsx" after the first step is over
- run "python second_step.py" and you will find everything is DONE!

## Last but not least
If you have any questions <strong>about the code</strong>, or any suggestions.
It will be my pleasure to have a discussion in the "issue" part.
But if you have problems in process this program, I am so sorry.
Every PC have different environment, just check out Google please.
Please respect everyone's time.

## 中文版说明
- 配置环境。注意如果你不能获取Chrome版本的selenium调试文件，我建议你换成Firefox，并将代码中的Chrome()换成Firefox()
- 编辑"first_step.py"，把url换成你要爬取的博主的url
- （注意：这个url带有/p/，你可以在手机版网页下，点击评论中博主的头像找到这个网址，记得无限下拉是可以看到全部微博的哦）
- 保存文件，执行"python first_step"
- 在浏览器中输入weibo.com，并立刻登录！且不要关闭这个网址！
- 执行"python second_step.py"，当然你也可以先去看看"link.xlsx"，第一步是否正常运行
- 完成！

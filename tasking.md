# Make-online-exam-interactive-page题目划分

![](TASKING.JPG)

```
#1 calculateScore
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score1:Number
#2 calcBlankFillingQuestions
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score2:Number
#3 calcSingleChoiceQuestions
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score3:Number
#4 calcMultipleChoiceQuestions
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score4:Number
#5 calcJudgementQuestions
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score5:Number
#6 calcShortAnswerQuestions
输入：
 score1:Number
 score2:Number
 score3:Number
 score4:Number
 score5:Number
输出：
 totalScore:Number
#7 calcScore
输入：
 questions：[{name, answer}]
 scoreForEachQuestion:Number
 judge:function
输出：
 score:Number
```


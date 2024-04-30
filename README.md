# searchAnswer
盐师 继续教育 网课 搜题工具

# 根据题目关键词 对题库内容进行搜索 

# 如何新增题库

json文件的结构体如下：  
```go  
type Answer struct {
	QuestionType string `json:"questionType"`
	Question     string `json:"question"`
	Answer       string `json:"answer"`
}
```
可自由新增题目和答案

## 操作演示

![PixPin_2024-04-30_09-50-33](https://github.com/wrysunny/searchAnswer/assets/20748454/9eb02713-2cdc-499c-945d-f89649e078f0)

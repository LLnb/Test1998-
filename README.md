    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>

48

    ·

49

    <a href="/docs/readme_it.md">Italiano</a>

50

    ·

51

    <a href="/docs/readme_kr.md">한국어</a>

52

  </p>

53

</p>

54

<p align="center">喜欢这个项目？请考虑<a href="https://www.paypal.me/anuraghazra">捐赠</a>来帮助它完善！

55

​

56

# 特性

57

​

58

- [GitHub 统计卡片](#GitHub-统计卡片)

59

- [GitHub 更多置顶](#GitHub-更多置顶)

60

- [热门语言卡片](#热门语言卡片)

61

- [主题](#主题)

62

- [自定义](#自定义)

63

- [自己部署](#自己部署)

64

​

65

# GitHub 统计卡片

66

​

67

将这行代码复制到你的 markdown 文件中，就是如此简单！

68

​

69

更改 `?username=` 的值为你的 GitHub 用户名。

70

​

71

```md

72

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

73

```

74

​

75

_注: 等级基于用户的统计信息计算得出，详见 [src/calculateRank.js](../src/calculateRank.js)_

76

​

77

### 隐藏指定统计

78

​

79

想要隐藏指定统计信息，你可以调用参数 `?hide=`，其值用 `,` 分隔。

80

​

81

> 选项：`&hide=stars,commits,prs,issues,contribs`

82

​

83

```md

84

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)

85

```

86

​

87

### 将私人项目贡献添加到总提交计数中

88

​

89

你可以使用参数 `?count_private=true` 把私人贡献计数添加到总提交计数中。

90

​

91

_注：如果你是自己部署本项目，私人贡献将会默认被计数，如果不是自己部署，你需要分享你的私人贡献计数。_

92

​

93

> 选项: `&count_private=true`

94

​

95

```md

96

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)

97

```

98

​

99

### 显示图标

100

​

101

如果想要显示图标，你可以调用 `show_icons=true` 参数，像这样：

102

​

103

```md

104

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)

105

```

106

​

107

### 主题


# AlphaLexClassicalChinese

This is the repository for **AlphaLexClassicalChinese**, a tool that automatically calculates the lexical complexity of Classical Chinese texts as described in the article below: 

雷蕾 & 韦瑶瑜. (2025). 古代汉语词汇复杂度：指标体系与测量工具. 外语电化教学, (6), 18–25.

[Lei, Lei & Wei, Yaoyu. (2025). Lexical Complexity in Classical Chinese: A Framework of Indices and a Measurement Tool. _Technology Enhanced Foreign Language Education_, (6), 18–25. ]

雷蕾 & 韦瑶瑜 (2025) is an extension to **AlphaLexChinese**, which is a tool that automatically calculates the lexical complexity of Chinese texts and described in detail in the article below: 

Zhang, H., & Lei, L. (2025). AlphaLexChinese: Measuring lexical complexity in Chinese texts and its predictive validity for L2 writing scores. System, 103809. https://doi.org/10.1016/j.system.2025.103809

You can also take a look at **AlphaLexChinese** at: 

https://github.com/corpustalk/AlphaLexChinese

## Download

See Releases of this repository on the right side of the page. 

## Copyright

AlphaLexClassicalChinese is designed by Lei Lei, and developed by Lei Lei (Shanghai International Studies University) and Haobo Zhang (Shanghai International Studies University). 

Contact: leileicnATqq.com

# How to use AlphaLexClassicalChinese

## Step 1

You need to first parse your Classical Chinese texts with a Yasuoka BERT model. See the files for the methods. 

  - Showcase_parsing_Classical_Chinese_with_Yasuoka_models.ipynb
  
  - Showcase_parsing_Classical_Chinese_with_Yasuoka_models.pdf

Save your parsed texts as .csv files.  

## Step 2

Open AlphaLexClassicalChinese.app, load a parsed text or a folder of many parsed texts, and calculate the lexical complexity of the text/s. 

## For Mac users

1. After you have downloaded AlphaLexClassicalChinese.dmg, double click it, and move AlphaLexClassicalChinese.app to the Applications folder.
2. Open terminal, go to the Applications folder, and type and run the following command in terminal.
3. Then open AlphaLexClassicalChinese.app and play with it. 

`sudo xattr -cr /Applications/AlphaLexClassicalChinese.app`

## Citations

If you use AlphaLexClassicalChinese, please kindly cite our articles:

- 雷蕾 & 韦瑶瑜. (2025). 古代汉语词汇复杂度：指标体系与测量工具. 外语电化教学, (6), 18–25.

- [Lei, Lei & Wei, Yaoyu. (2025). Lexical Complexity in Classical Chinese: A Framework of Indices and a Measurement Tool. _Technology Enhanced Foreign Language Education_, (6), 18–25. ]

- Zhang, H., & Lei, L. (2025). AlphaLexChinese: Measuring lexical complexity in Chinese texts and its predictive validity for L2 writing scores. _System_, 103809. https://doi.org/10.1016/j.system.2025.103809


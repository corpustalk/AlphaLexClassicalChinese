
# AlphaLexClassicalChinese

This is the repository for **AlphaLexClassicalChinese**, a tool that automatically calculates the lexical complexity of Classical Chinese texts as described in the article below: 

雷蕾、韦瑶瑜. (2025). 古代汉语词汇复杂度：指标体系与测量工具. 外语电化教学, (6), 18–25.

[Lei, Lei & Wei, Yaoyu. (2025). Lexical Complexity in Classical Chinese: A Framework of Indices and a Measurement Tool. _Technology Enhanced Foreign Language Education_, (6), 18–25. ]

## Download

See Releases of this repository on the right side of the page. 

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

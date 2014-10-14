# hsk-words

hsk-words is a "batteries-included" library for querying the Chinese Government's HSK (汉语水平考试) word list. This is a test used for university admission for foreigners in the PRC and includes 5,000 words in the list across all 6 levels.

## Usage

```
var hsk = require('hsk-words');

hsk.findLevel('学习', function(level){
  // level evaluates to -1 if not found, else is in 1..6
  console.log(level);
});

```

## License

MIT
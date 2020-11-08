# Preprocessing and postediting tools especially for NLP

Natural Language Processing သုတေသန လုပ်ကြတော့မယ်ဆိုရင် အရင်ဆုံး text file တွေကို cleaning လုပ်တာ၊ encoding ပြောင်းတာ၊
ရှိနေတဲ့ format ကို ကိုယ်လိုချင်တဲ့ ပုံစံဖြစ်အောင် ပြောင်းရတာ၊ လိုချင်တဲ့ စာလုံးတွေ၊ စာကြောင်းတွေကိုပဲ ဆွဲထုတ်ယူတာ စသည်ဖြင့် လုပ်ရတဲ့ အလုပ်တွေက အများကြီးပါပဲ။
Experiment တွေကို လုပ်ဖို့အတွက်က နေ့စဉ်လိုလို shell, perl (အခုနောက်ပိုင်းမှာတော့ python language) နဲ့ ပရိုဂရမ်တွေကို ရေးကြရပါတယ်။ တစ်ခါတလေမှာ format တစ်ခုကနေ နောက်တခြား format တစ်ခုကို ပြောင်းဖို့အတွက် ပရိုဂရမ်တပုဒ်ကို တရက်လုံးအချိန်ပေးပြီး ရေးလိုက်ရတာမျိုးလည်း ရှိပါတယ်။ အဲဒါကြောင့် အသုံးဝင်နိုင်မယ့် bash, perl, python ပရိုဂရမ်တွေကို ကျွန်တော် အချိန်ရရင်ရသလို တင်ပေးသွားပါမယ်။ တစ်ခုမှာချင်တာက ကျွန်တော်တင်ပေးထားတဲ့ ပရိုဂရမ်တွေကို အခြေခံပြီးတော့ shell, perl scripts တွေကို ကိုယ်တိုင်ရေးနိုင်အောင် ကြိုးစားကြပါ။ 

သုံးပုံသုံးနည်း အသေးစိတ်ကိုတော့ သက်ဆိုင်ရာ ဖိုလ်ဒါအသီးသီးမှာ ရှိတဲ့ **example-usages.md** ([for bash](https://github.com/ye-kyaw-thu/tools/blob/master/bash/example-usages.md), [for perl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/example-usages.md), [for python](https://github.com/ye-kyaw-thu/tools/blob/master/python/example-usages.md)) ဖိုင်တွေကို မှီငြမ်းပါ။   

ရဲကျော်သူ

# bash

1. [read-and-move.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/read-and-move.sh)  
2. [change-filenames.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/change-filenames.sh)  
3. [rm-date-sentences.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-date-sentences.sh)  
4. [print-classID-prediction-result.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-classID-prediction-result.sh)
5. [compare-img-or-pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/compare-img-or-pdf.sh)  
6. [chk-sort-by-columns.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/chk-sort-by-columns.sh)  
7. [kill-all-detached.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/kill-all-detached.sh)  
8. [unzip-all-with-one-passwd.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/unzip-all-with-one-passwd.sh)  
9. [cut-filename.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/cut-filename.sh)  
10. [calc-avg.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/calc-avg.sh)  
11. [print-latex-section.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-latex-section.sh)  
12. [list-mistake-5-suggestion.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/list-mistake-5-suggestion.sh)  
13. [mytxt2pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mytxt2pdf.sh)  
14. [prepare-open-test-data.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/prepare-open-test-data.sh)  
15. [print-CRLF.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-CRLF.sh)  
16. [group-files.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/group-files.sh)  
17. [segmentation.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/segmentation.sh)  
18. [split-even-odd-pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/split-even-odd-pdf.sh)  
19. [even-odd.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/even-odd.sh)  
20. [rm-stopwords.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-stopwords.sh)  
21. [rm-spaces-lineno.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-spaces-lineno.sh)  
22. [blowfish.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/blowfish.sh)  
23. [replace-with-lineno.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/replace-with-lineno.sh)  
24. [replace-with-lineno2.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/replace-with-lineno2.sh) 
25. [OOV-count.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/OOV-count.sh)  
26. [find-blank-lines.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/find-blank-lines.sh)  
27. [dot2png-pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/dot2png-pdf.sh)  
28. [add-start-end.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/add-start-end.sh)  
29. [get-words-with-position.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/get-words-with-position.sh)  
30. [count-string-length.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/count-string-length.sh)  
31. [strip-substring.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/strip-substring.sh)  
32. [chk_total_duration.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/chk_total_duration.sh)  
33. [print-sentenceID-count.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-sentenceID-count.sh)  
34. [mk-16KHz-mono.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-16KHz-mono.sh)  
35. [mk-spectrogram.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-spectrogram.sh)  
36. [group-UCF11.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/group-UCF11.sh)  
37. [group-within-group-UCF11.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/group-within-group-UCF11.sh) 
38. [dot2pic.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/dot2pic.sh)  
39. [2mono-pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/2mono-pdf.sh)  
40. [calc-bleu-all.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/calc-bleu-all.sh)  
41. [calc-ribes-all.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/calc-ribes-all.sh)  
42. [print-matched-x.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-matched-x.sh)  
43. [split-train-dev-test.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/split-train-dev-test.sh)  
44. [clean-space-all.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/clean-space-all.sh)  
45. [mk-g2p-model.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-g2p-model.sh)  
46. [mk-syl-list.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-syl-list.sh)  
47. [rm-200b-200d.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-200b-200d.sh)  
48. [print-char.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-char.sh)    
49. [prepare-10fold-smt-pair.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/prepare-10fold-smt-pair.sh)  
50. [rm-ctrl-m.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-ctrl-m.sh)  
51. [x-letter-word.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/x-letter-word.sh)  
52. [paste-column.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/paste-column.sh)  
53. [lm-building-exec.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/lm-building-exec.sh)  
54. [print-most-common.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-most-common.sh)  
55. [calc-ppl-with-kenlm-query.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/calc-ppl-with-kenlm-query.sh)  
56. [mk-two-lm-and-merge.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-two-lm-and-merge.sh)  
57. [mk-class-lm.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-class-lm.sh)  
58. [get-myPOS-tag.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/get-myPOS-tag.sh)  
59. [rm-myPOStags.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-myPOStags.sh)  
60. [print-same-col1.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/print-same-col1.sh)  
61. [char-segmentation.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/char-segmentation.sh)  
62. [chk-blank-fields.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/chk-blank-fields.sh)  
63. [chk-field-length.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/chk-field-length.sh)  
64. [crop-pdf.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/crop-pdf.sh)  
65. [excel2csv-chk-fields.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/from65/excel2csv-chk-fields.sh)  
66. [change-format.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/change-format.sh)  
67. [format-mecab-pos.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/format-mecab-pos.sh)  
68. [cp-config.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/cp-config.sh)  
69. [DELETE-ALL.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/DELETE-ALL.sh)  
70. [trim-silence.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/trim-silence.sh)  
71. [wav2wavform.sh](https://github.com/ye-kyaw-thu/tools/edit/master/bash/wav2wavform.sh)  
72. [mytext2pic.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mytext2pic.sh)  
73. [formula-pic.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/formula-pic.sh)  
74. [rm-heading-tab-lineno.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rm-heading-tab-lineno.sh)  
75. [mk-10cross-data.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mk-10cross-data.sh)  
76. [align-GIZA++.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/align-GIZA%2B%2B.sh)  
77. [date-time-info.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/date-time-info.sh)  
78. [mp4-to-wav.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mp4-to-wav.sh)  
79. [my-font-chk.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/my-font-chk.sh)  
80. [rec-recorder.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/rec-recorder.sh)    
81. [mp42gif.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/mp42gif.sh)  
82. [extract-target-text.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/extract-target-text.sh)  
83. [txt2png.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/txt2png.sh)  
84. [pic2histogram.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/pic2histogram.sh)  
85. [tesseract-ocr.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/tesseract-ocr.sh)  
86. [sylbreak-10fold-mt.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/sylbreak-10fold-mt.sh)  
87. [syllable-break-multi-files.sh](https://github.com/ye-kyaw-thu/tools/blob/master/bash/syllable-break-multi-files.sh)  

# perl

1. [clean-space.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/clean-space.pl)
2. [rm-EnglishSentences.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-EnglishSentences.pl)
3. [word-analysis.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/word-analysis.pl)
4. [print-emojiSentences.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-emojiSentences.pl)
5. [dq-multilines.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/dq-multilines.pl)  
6. [mk-abstract-para.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/mk-abstract-para.pl)  
7. [print-mySentenceOnly.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-mySentenceOnly.pl)  
8. [rm-symbol-and-myVowel-only-sentences.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-symbol-and-myVowel-only-sentences.pl)  
9. [rm-space-btw-numbers.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-space-btw-numbers.pl)  
10. [print-ngram.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-ngram.pl)  
11. [print-codepoint.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-codepoint.pl)  
12. [wc.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/wc.pl)  
13. [wordlimit.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/wordlimit.pl)  
14. [wordwrap.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/wordwrap.pl)  
15. [get-syl-potma.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/get-syl-potma.pl)  
16. [my-linebreak.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/my-linebreak.pl)  
17. [rm-ne-tag.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-ne-tag.pl)  
18. [clean-v-without-c.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/clean-v-without-c.pl)  
19. [x-x-to-x-comma-x-with-brackets.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/x-x-to-x-comma-x-with-brackets.pl)  
20. [select-en-th-my.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/select-en-th-my.pl)  
21. [mk-speakers-json.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/mk-speakers-json.pl)  
22. [string-distance.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/string-distance.pl)  
23. [print-matched-char-seq.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-matched-char-seq.pl)  
24. [search-common.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/search-common.pl) 
25. [fixed-parallel-order.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/fixed-parallel-order.pl)  
26. [encode-input.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/encode-input.pl)  
27. [decode.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/decode.pl)  
28. [mk-one2one-freq.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/mk-one2one-freq.pl)  
29. [mk-one-syl-confusion.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/mk-one-syl-confusion.pl)  
30. [rm-onechar-line.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-onechar-line.pl)  
31. [replace-with-lineno.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/replace-with-lineno.pl)  
32. [chk-pos-tags.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/chk-pos-tags.pl) 
33. [count-string-length.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/count-string-length.pl)  
34. [print-diff-word.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-diff-word.pl)  
35. [print-union-isect-diff.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-union-isect-diff.pl)  
36. [print-common-kachin.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-common-kachin.pl)  
37. [sylbreak.pm](https://github.com/ye-kyaw-thu/tools/blob/master/perl/sylbreak.pm)  
38. [test.sylbreak.pm.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/test.sylbreak.pm.pl)  
39. [tag-BI.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/tag-BI.pl)  
40. [bigram-similarity.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/bigram-similarity.pl)  
41. [chk-src-trg-words.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/chk-src-trg-words.pl)  
42. [print-my-numeric-sentence.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-my-numeric-sentence.pl)  
43. [number-punct-segmentation.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/number-punct-segmentation.pl)  
44. [tabpair-to-crfcol.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/tabpair-to-crfcol.pl)  
45. [print-blank-lines.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-blank-lines.pl)  
46. [add-spu_id.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/add-spu_id.pl)  
47. [human-mt-eval-form.pl](https://github.com/ye-kyaw-thu/tools/edit/master/perl/human-mt-eval-form.pl)  
48. [trainTuneScore_jamy.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/trainTuneScore_jamy.pl)  
49. [rm-blank-line.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/rm-blank-line.pl)  
50. [gizaA3-4human.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/gizaA3-4human.pl)  
51. [print-fngram-format.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-fngram-format.pl)  
52. [print-myWordOnly.pl](https://github.com/ye-kyaw-thu/tools/blob/master/perl/print-myWordOnly.pl)  

# Python

1. [rm-blank-line.plchk-token.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/chk-token.py)  
2. [numpy-array-element-compare.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/numpy-array-element-compare.py)  
3. [char-count-element-wise.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/char-count-element-wise.py) 
4. [char-startswith-element-wise.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/char-startswith-element-wise.py) 
5. [fuzzy-match.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/fuzzy-match.py)  
6. [hex2uni.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/hex2uni.py)  
7. [korean-breaks.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/korean-breaks.py)  
8. [epitranscribe.py](https://github.com/ye-kyaw-thu/tools/blob/master/python/epitranscribe.py)  



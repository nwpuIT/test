# test
This is test version<br>
python test.py --model<br>
 bash:<br>
    　jelly<br>
   　　 the space
需要注意的是要换行的时候不能直接通过回车来换行，需要使用<br>
显示空格的小Tip　　把你的输入法由半角改成全角就OK啦。\<<br>
 要显示一个超链接的话，就直接输入这个链接的URL就好了 <br>
 
 
 ## Requirements

- `Pytorch 0.3.0` or newer
- `Python 3.6`
- `Perl`

## Usage

- Training and Prediction

  ```bash
  python main.py [-h] [--train-data-path TRAIN_DATA_PATH]
                 [--test-data-path TEST_DATA_PATH]
                 [--slot-names-path SLOT_NAMES_PATH]
                 [--saved-model-path SAVED_MODEL_PATH]
                 [--result-path RESULT_PATH] [--mode {elman,jordan,hybrid,lstm}]
                 [--bidirectional] [--cuda]
  ```
 eg: python main.py --train-data-path TRAIN_DATA_PATH
- [Evaluation](./eval/conlleval.md)

  ```bash
  perl eval/conlleval.pl -d "\t" < data/output.txt
  ```

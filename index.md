[comment]: <> (This is a comment, it will not be included)
[comment]: <> (in  the output file unless you use it in)
[comment]: <> (a reference style link.)

## PitchGAN: A Conditional GAN Generating Pitch Curve for Singing Voice Synthesis
contact: huiranyu@andrew.cmu.edu
### Sound Examples

The sound examples are from four models: the proposed PitchGAN; PitchGAN trained with the sum of GAN loss and MSE loss; generator in PitchGAN trained with MSE loss; the CNN-LSTM baseline model. The original audios from an amatuer singer are also listed here for reference.

|  SongID_start:end   | GAN(proposed) | GAN + MSE | Generator + MSE | CNN-LSTM + MSE  | Origin Audio |
|  :----:             | :----:        | :----:    | :----:          | :----:          | :----:       |
| 8765_21:51          | <audio src="test_set/8765_21_51/gan.mp3" controls></audio> | <audio src="test_set/8765_21_51/ganmse.mp3" controls></audio> | <audio src="test_set/8765_21_51/mse.mp3" controls></audio> | <audio src="test_set/8765_21_51/baseline.mp3" controls></audio> | <audio src="test_set/8765_21_51/origin.mp3" controls></audio> |
| 8765_101:132        | <audio src="test_set/8765_101_132/gan.mp3" controls></audio> | <audio src="test_set/8765_101_132/ganmse.mp3" controls></audio> | <audio src="test_set/8765_101_132/mse.mp3" controls></audio> | <audio src="test_set/8765_101_132/baseline.mp3" controls></audio> | <audio src="test_set/8765_101_132/origin.mp3" controls></audio> |
| 77374_49:75         | <audio src="test_set/77374_49_75/gan.mp3" controls></audio> | <audio src="test_set/77374_49_75/ganmse.mp3" controls></audio> | <audio src="test_set/77374_49_75/mse.mp3" controls></audio> | <audio src="test_set/77374_49_75/baseline.mp3" controls></audio> | <audio src="test_set/77374_49_75/origin.mp3" controls></audio> |
| 3198354_7:34        | <audio src="test_set/3198354_7_34/gan.mp3" controls></audio> | <audio src="test_set/3198354_7_34/ganmse.mp3" controls></audio> | <audio src="test_set/3198354_7_34/mse.mp3" controls></audio> | <audio src="test_set/3198354_7_34/baseline.mp3" controls></audio> | <audio src="test_set/3198354_7_34/origin.mp3" controls></audio> |

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ella-granger/ella-granger.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

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

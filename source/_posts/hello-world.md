---
title: Reconstruction of perceived and imagined music from non-invasive EEG with generative adversarial networks
---

<!--{% asset_img EEG2Music.png Imagined %}-->

**Reconstructing auditory stimulus from human neural signals is an emerging and challenging direction in the brain-computer interface (BCI) field. In this paper, we propose an end-to-end deep learning decoding strategy based on generative adversarial networks (GANs) to reconstruct perceived and imagined music from noninvasive EEG signals. The input of our generator is the pre-processed EEG signal without additional feature extraction steps. The generator’s output is the raw musical waveforms, without the need to use a vocoder or Griffi-Lim algorithm to synthesize music from mel-spectrogram.**

**We evaluate the reconstruction performance on two public EEG datasets. The reconstruction results show that the proposed reconstruction strategy has great performance on several subjective and objective evaluation metrics, and the reconstructed music has good audio quality. The cross-subject results in the first dataset further show the strong generalization ability of the proposed model, which might indicate the potential of reconstructing music from new subjects, for example, a patient who lost the ability of music expression due to brain injury.**

**The results in this paper can help us have a better understanding of the dynamic neural coding characteristics of music cognition in human brain. In addition, the proposed reconstruction strategy can be easily transplanted into the speech brain-computer interface scenario, to help patients regain the ability of language and music expression, and even communicate like normal people with natural speed and unlimited vocabulary, which has great significance for neuroscience research and clinical treatment.**

## Dataset 1: NMED-Tempo (Perceived music)

*8The first dataset is Naturalistic Music EEG Dataset—Tempo (NMED-T), an open dataset of electrophysiological and behavioral responses collected from 20 participants who heard a set of 10 commercially available musical works. The EEG data were continuously recorded from 128 electrodes at a sampling rate of 1 kHz. We reconstruct perceived music from this dataset.**

### song 1

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song1_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song1_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song1_2.png Recon2 %} </th>
          </tr>
        </tbody></table>

### song 2

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song2_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song2_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song2_2.png Recon2 %} </th>
          </tr>
        </tbody></table>

### song 3

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song3_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song3_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song3_2.png Recon2 %} </th>
          </tr>
        </tbody></table>
        
### song 4

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song4_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song4_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song4_2.png Recon2 %} </th>
          </tr>
        </tbody></table>
        
### song 5

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song5_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song5_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song5_2.png Recon2 %} </th>
          </tr>
        </tbody></table>

### song 6

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song6_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song6_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song6_2.png Recon2 %} </th>
          </tr>
        </tbody></table>       

### song 7

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song7_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song7_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song7_2.png Recon2 %} </th>
          </tr>
        </tbody></table>           

### song 8

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song8_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song8_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song8_2.png Recon2 %} </th>
          </tr>
        </tbody></table>    

### song 9

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song9_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song9_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song9_2.png Recon2 %} </th>
          </tr>
        </tbody></table>    

### song 10

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music 1</th>
            <th style="text-align: center">Reconstructed Music 2</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub1_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub2_recon_nr_new_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song10_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song10_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song10_2.png Recon2 %} </th>
          </tr>
        </tbody></table>    
        
## Dataset 2: The music of silence (MOS) (Perceived and imagined music)

<!--{% asset_img EEG2Mel2Music.png Imagined %}-->
**The second dataset is from [1], which we call “The music of silence”, “MOS” for short. All 21 participants in this dataset were chosen to be very well-trained musicians. The experiment consisted of two conditions, listening and imagery. In the listening condition, participants were asked to passively listen to the four melodies from the corpus of Bach chorals while reading the musical score. For the imagery condition, they were asked to imagine the melodies in sync with the tactile metronome as precisely as they could. The provided preprocessed EEG data were down-sampled to 64 Hz and re-referenced to the average of all 64 channels. We reconstruct perceived and imagined music from this dataset.**

[1] G. Marion, G. M. D. Liberto, and S. A. Shamma, ‘The Music of Silence: Part I: Responses to Musical Imagery Encode Melodic Expectations and Acoustics’, J Neurosci, vol. 41, no. 35, pp. 7435–7448, Sep. 2021, doi: 10.1523/JNEUROSCI.0183-21.2021.

### melody 1

<table width="900" height="235" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img melody1.jpg Original %} </th>
            <th style="text-align: center"> {% asset_img melody1_P.jpg Perceived %} </th>
            <th style="text-align: center"> {% asset_img melody1_I.jpg Imagined %} </th>
          </tr>
        </tbody></table>

### melody 2

<table width="900" height="235" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_P_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img melody2.jpg Original %} </th>
            <th style="text-align: center"> {% asset_img melody2_P.jpg Perceived %} </th>
            <th style="text-align: center"> {% asset_img melody2_I.jpg Imagined %} </th>
          </tr>
        </tbody></table>
        
### melody 3

<table width="900" height="235" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img melody3.jpg Original %} </th>
            <th style="text-align: center"> {% asset_img melody3_P.jpg Perceived %} </th>
            <th style="text-align: center"> {% asset_img melody3_I.jpg Imagined %} </th>
          </tr>
        </tbody></table>
                
### melody 4

<table width="900" height="235" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_P_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_I.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img melody4.jpg Original %} </th>
            <th style="text-align: center"> {% asset_img melody4_P.jpg Perceived %} </th>
            <th style="text-align: center"> {% asset_img melody4_I.jpg Imagined %} </th>
          </tr>
        </tbody></table>

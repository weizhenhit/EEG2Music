---
title: Reconstruction of perceived and imagined music from non-invasive EEG with generative adversarial networks
---

{% asset_img EEG2Wav.png Imagined %}

**Reconstructing auditory stimulus from human neural signals is an emerging and challenging direction in the brain-computer interface (BCI) field. In this paper, we propose an end-to-end deep learning decoding strategy based on generative adversarial networks (GANs) to reconstruct perceived and imagined music from noninvasive EEG signals. The input of our generator is the pre-processed EEG signals without additional feature extraction steps. The generator’s output is the raw musical waveforms, without the need to use a vocoder or Griffi-Lim algorithm to synthesize music from mel-spectrogram.**

**We evaluated the reconstruction performance on two public EEG datasets. The reconstruction results showed that the proposed reconstruction strategy had great performance on several subjective and objective quality assessments, and the reconstructed music has good audio quality. The successful reconstruction of unseen imagined songs and the cross-subject results further demonstrated the strong generalization ability of the proposed model, which might indicate the potential of decoding new songs from new subjects, for example, a patient who lost the ability to music expression due to brain injury.**

**In addition, the proposed reconstruction strategy can be easily transplanted into the speech brain-computer interface scenario, to help patients regain the ability of language and music expression, and even communicate like normal people with natural speed and unlimited vocabulary, which has great significance for neuroscience research and clinical treatment.**

**In summary, our results shed new light on reconstructing high-quality auditory stimulus from noninvasive EEG signals and prove the powerful potential of generative models in bridging BCI and AI.**


## Dataset 1: NMED-Tempo (Perceived music)

The first dataset is Naturalistic Music EEG Dataset—Tempo (NMED-T), an open dataset of electrophysiological and behavioral responses collected from 20 participants who heard a set of 10 commercially available musical works. The EEG data were continuously recorded from 128 electrodes at a sampling rate of 1 kHz. We reconstruct perceived music from this dataset.

### song 1

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8_sub2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9_sub2_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song9_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song9_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song9_2.png Recon2 %} </th>
          </tr>
        </tbody></table>    

### song 10 (unseen song)

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Music</th>
            <th style="text-align: center">Reconstructed Music (Participant 1)</th>
            <th style="text-align: center">Reconstructed Music (Participant 2)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub2_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song10_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img song10_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img song10_2.png Recon2 %} </th>
          </tr>
        </tbody></table>    

<table width="800" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Reconstructed Music (Participant 3)</th>
            <th style="text-align: center">Reconstructed Music (Participant 4)</th>
            <th style="text-align: center">Reconstructed Music (Participant 5)</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub3_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub4_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub5_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img song10_3.png Recon3 %} </th>
            <th style="text-align: center"> {% asset_img song10_4.png Recon4 %} </th>
            <th style="text-align: center"> {% asset_img song10_5.png Recon5 %} </th>
          </tr>
        </tbody></table>    
        
## Dataset 2: The music of silence (MOS) (Perceived and imagined music)

<!--{% asset_img EEG2Mel2Music.png Imagined %}-->
The second dataset is from [1], which we call “The music of silence”, “MOS” for short. All 21 participants in this dataset were chosen to be very well-trained musicians. The experiment consisted of two conditions, listening and imagery. In the listening condition, participants were asked to passively listen to the four melodies from the corpus of Bach chorals while reading the musical score. For the imagery condition, they were asked to imagine the melodies in sync with the tactile metronome as precisely as they could. The provided preprocessed EEG data were down-sampled to 64 Hz and re-referenced to the average of all 64 channels. We reconstruct perceived and imagined music from this dataset.

[1] G. Marion, G. M. D. Liberto, and S. A. Shamma, ‘The Music of Silence: Part I: Responses to Musical Imagery Encode Melodic Expectations and Acoustics’, J Neurosci, vol. 41, no. 35, pp. 7435–7448, Sep. 2021, doi: 10.1523/JNEUROSCI.0183-21.2021.

### melody 1

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_P_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 1_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 1_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 1_2.png Imagined %} </th>
          </tr>
        </tbody></table>

### melody 1 (unseen)

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_unseen_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_P_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody1_I_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 1_0_un.png Original %} </th>
            <th style="text-align: center"> {% asset_img 1_1_un.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 1_2_un.png Imagined %} </th>
          </tr>
        </tbody></table>
        
### melody 2

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_en.wav" type="audio/mpeg">
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
            <th style="text-align: center"> {% asset_img 2_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 2_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 2_2.png Imagined %} </th>
          </tr>
        </tbody></table>

### melody 2 (unseen)

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_unseen_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_P_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody2_I_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 2_0_un.png Original %} </th>
            <th style="text-align: center"> {% asset_img 2_1_un.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 2_2_un.png Imagined %} </th>
          </tr>
        </tbody></table>
        
### melody 3

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_P_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 3_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 3_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 3_2.png Imagined %} </th>
          </tr>
        </tbody></table>

### melody 3 (unseen)

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_unseen_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_P_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody3_I_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 3_0_un.png Original %} </th>
            <th style="text-align: center"> {% asset_img 3_1_un.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 3_2_un.png Imagined %} </th>
          </tr>
        </tbody></table>
                
### melody 4

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_P_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_I_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 4_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 4_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 4_2.png Imagined %} </th>
          </tr>
        </tbody></table>

### melody 4 (unseen)

<table width="900" height="300" border="1">
          <tbody><tr class="table_title">
            <th style="text-align: center">Original Melody</th>
            <th style="text-align: center">Reconstructed Perceived Melody</th>
            <th style="text-align: center">Reconstructed Imagined Melody</th>
          </tr>
          <tr class="table_audio">
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_unseen_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_P_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody4_I_un_en.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 4_0_un.png Original %} </th>
            <th style="text-align: center"> {% asset_img 4_1_un.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 4_2_un.png Imagined %} </th>
          </tr>
        </tbody></table>

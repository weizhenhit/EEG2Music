---
title: Reconstruction of perceived and imagined music from non-invasive EEG with generative adversarial networks (EEG2Mel-GAN)
---

{% asset_img EEG2Mel.png Imagined %}

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
                <source src="/EEG2Music/pic/song1_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song1_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 1_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 1_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 1_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song2_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song2_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 2_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 2_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 2_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song3_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song3_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 3_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 3_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 3_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song4_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song4_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 4_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 4_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 4_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song5_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song5_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 5_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 5_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 5_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song6_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song6_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 6_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 6_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 6_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song7_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song7_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 7_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 7_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 7_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song8_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song8_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 8_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 8_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 8_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song9_sub1_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song9_sub2_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 9_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 9_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 9_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song10_sub3_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub6_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 10_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 10_1.png Recon1 %} </th>
            <th style="text-align: center"> {% asset_img 10_2.png Recon2 %} </th>
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
                <source src="/EEG2Music/pic/song10_sub7_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub19_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/song10_sub20_t0_recon.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 10_3.png Recon3 %} </th>
            <th style="text-align: center"> {% asset_img 10_4.png Recon4 %} </th>
            <th style="text-align: center"> {% asset_img 10_5.png Recon5 %} </th>
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
                <source src="/EEG2Music/pic/melody19_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody19_I.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 19_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 19_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 19_2.png Imagined %} </th>
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
                <source src="/EEG2Music/pic/melody38_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody38_I.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 38_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 38_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 38_2.png Imagined %} </th>
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
                <source src="/EEG2Music/pic/melody96_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody96_I.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 96_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 96_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 96_2.png Imagined %} </th>
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
                <source src="/EEG2Music/pic/melody101_P.wav" type="audio/mpeg">
              </audio>
            </th>
            <th style="text-align: center">
              <audio controls>
                <source src="/EEG2Music/pic/melody101_I.wav" type="audio/mpeg">
              </audio>
            </th>
          </tr>
          <tr class="table_title">
            <th style="text-align: center"> {% asset_img 101_0.png Original %} </th>
            <th style="text-align: center"> {% asset_img 101_1.png Perceived %} </th>
            <th style="text-align: center"> {% asset_img 101_2.png Imagined %} </th>
          </tr>
        </tbody></table>


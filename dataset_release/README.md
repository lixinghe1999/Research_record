## Dataset of multi-modal audio (air-conducted and bone-conducted)
### 1. [Version1: Raspberry Pi](https://mycuhk-my.sharepoint.com/:f:/g/personal/1155170464_link_cuhk_edu_hk/EiBk2p45s3RMiao70y4SZE8BFmgQNgSyTUBGj2G35d8t_A?e=5wpxDF):
    - 8 subjects 
    - 3 types of recordings: 
        - clean (recording without noise)
        - noise (recording under noise)
        - none (stay silent)
    - file name format:
        - bmiacc1_{time()}.txt: IMU1 recording
        - bmiacc2_{time()}.txt: IMU2 recording
        - mic_{time()}.wav: high-quality (Logitech) microphone recording
        - 录音(recording)_{}.m4a: iPhone recording
    - how to load:
        - audio: normal audio loading
        - IMU: [X, Y, Z, Timestamp (s)] 
#### How to collect? see [here](https://github.com/lixinghe1999/Raspberry-Pi/tree/main)

### 2. [Version2: Knowles](https://mycuhk-my.sharepoint.com/:f:/g/personal/1155170464_link_cuhk_edu_hk/EqW4np-yPG9LtQR9nY4TylIBRwL_cpeDpI4ol34BsrrAOA?e=r3GWIb)
    - 15 subjects
    - Record with Knowles V2S
    - Recording content: read AISHELL DATASET in Chinese
    - Record under random noises
    - Meta info provided
    - How to load? just like two-channel audio.

### 3. Other useful dataset
    - [ABCS](https://github.com/wangmou21/abcs)
    - [ESMB](https://github.com/elevoctech/ESMB-corpus)
    - [VibraVox](https://huggingface.co/datasets/Cnam-LMSSC/vibravox)


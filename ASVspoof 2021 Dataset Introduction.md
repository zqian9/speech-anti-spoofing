# ASVspoof 2021 数据集概览

1. 不再提供新的训练集和开发集，仅提供评估集作为性能评估。
2. 采用ASVspoof 2019的训练集和开发集
3. ASVspoof 2021 的评估集是基于ASVspoof 2019的评估集

### Logical Access (LA)

ASVspoof 2021 LA的评估集包括ASVspoof 2019 LA的评估集、及其经过六种处理的集合。

| Condition |   Codec    | Bnadwidth(kHz) | Transmission |
| :-------: | :--------: | :------------: | :----------: |
|    C1     |     -      |       16       |      -       |
|    C2     |   a-law    |       8        |     VoIP     |
|    C3     | unk.+μ-law |       8        |  PSTN+VoIP   |
|    C4     |   G.722    |       16       |     VoIP     |
|    C5     |    TBA     |       8        |     VoIP     |
|    C6     |    TBA     |       8        |     VoIP     |
|    C7     |    TBA     |       16       |     VoIP     |



### Physical Access (PA)

// TO DO

### Speech Deepfake (DF)

ASVspoof 2021 LA的评估集包括ASVspoof 2019 LA的评估集等其它的数据集、及其经过八种处理的集合。音频经过编码和解码的操作，而这个过程会引入失真。

| Condition | Compression | Variable Bit Rate |
| :-------: | :---------: | :---------------: |
|    C1     |      -      |         -         |
|    C2     |     mp3     |      ~80-120      |
|    C3     |     mp3     |     ~220-260      |
|    C4     |     m4a     |      ~20-32       |
|    C5     |     m4a     |      ~96-112      |
|    C6     |     ogg     |      ~80-96       |
|    C7     |     ogg     |     ~256-320      |
|    C8     |     TBA     |        TBA        |
|    C9     |     TBA     |        TBA        |



## References

[1] Yamagishi, J., Wang, X., Todisco, M., Sahidullah, M., Patino, J., Nautsch, A., Liu, X., Lee, K.A., Kinnunen, T., Evans, N., Delgado, H. (2021) ASVspoof 2021: accelerating progress in spoofed and deepfake speech detection. Proc. 2021 Edition of the Automatic Speaker Verification and Spoofing Countermeasures Challenge, 47-54, doi:10.21437/ASVSPOOF.2021-8
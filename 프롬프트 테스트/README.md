

---
![image](https://github.com/ReeELL/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00006-2324467698.png?raw=true)

parameters

prompt
```
a captivating close-up photo of a girl drawn in lo-fi style in her room, writing in a book, calm environment with a thoughtful expression, her spaghetti hair loose and flowing around her face with a single strand capturing a ray of light
Negative prompt: nsfw
```
Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2324467698, Size: 512x512, Model hash: 6ce0161689, Model: v1-5-pruned-emaonly, Version: 1.8.0-RC

---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/13dae5a308d7a36eef79146ec32802febbfe3288/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00003-200023648.png)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/1796204119f1ff256476b19ae9bb2a902db10c4e/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00002-277080419.png)
parameters

prompt
```
a girl with black hair, green eyes, amazed, standing, crouched, on the floor, in a blue dress and high shoes
Negative prompt: nsfw
```
Steps: 30, Sampler: DPM++ 3M SDE Karras, CFG scale: 7, Seed: 2624589988, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Version: 1.8.0-RC

# 인페이팅 테스트
---
![image](https://github.com/ReeELL/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00007-2764736762.png?raw=true)

![image](https://github.com/ReeELL/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00002-2203212081.png?raw=true)
parameters

prompt
```
1girl , (long hair:0.5), wearing stola, vast roman palace, large window, medieval renaissance palace, 4k, arstation, intricate, elegant, highly detailed
Negative prompt: worst quality, low quality, normal quality, unclear architectural outline, duplicate, missing_body, (missing_face:1.4), (missing_eyes:1.4), nsfw
```
Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2203212081, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Denoising strength: 0.89, Mask blur: 4, Inpaint area: Only masked, Masked area padding: 32, Version: 1.8.0-RC

# Img2Img 테스트
---
![image](https://github.com/ReeELL/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/2024-03-29%20095631.png?raw=true)

![image](https://github.com/ReeELL/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00001-1960479723.png?raw=true)
parameters

# prompt
```
masterpiece, high_quality, super_detail, CG_game_cg, a woman in a red hat and black skirt
Negative prompt: (painting by bad-artist-anime:0.9), (painting by bad-artist:0.9), watermark, text, error, blurry, jpeg artifacts, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, artist name, (worst quality, low quality:1.4), bad anatomy, watermark, signature, text, logo
```
Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1960479723, Size: 344x480, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Denoising strength: 0.45, ADetailer model: face_yolov8n.pt, ADetailer confidence: 0.3, ADetailer dilate erode: 4, ADetailer mask blur: 4, ADetailer denoising strength: 0.4, ADetailer inpaint only masked: True, ADetailer inpaint padding: 32, ADetailer version: 24.3.2, Mask blur: 4, Inpaint area: Only masked, Masked area padding: 32, Version: 1.8.0-RC

# 라인아트 테스트
---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/8910b8b8de866f26e1dafaffa8c4ae26cfef6aa9/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/64b17ad6ae3560d5394d44c6_lineart-anime-avatar.png)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/8910b8b8de866f26e1dafaffa8c4ae26cfef6aa9/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00002-3464506942.png)


```
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 3464506942, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: lineart_anime, Model: control_v11p_sd15_lineart [43d4be0d], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: 1.8.0-RC

```

# Scribble 테스트
---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/b80d18234cd5149d2ee7b92c7ff992d548a233b2/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B7%B8%EB%A6%BC%202.png)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/b80d18234cd5149d2ee7b92c7ff992d548a233b2/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00004-191751643.png)


```
lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl , hoodie, animal gloves, skirt, sneakers
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 191751643, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Crop and Resize, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: 1.8.0-RC

```

# Depth Test
---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/930d024636a20853bd326286ca3ed7afd3926dda/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202024-04-05%20103158.png)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/930d024636a20853bd326286ca3ed7afd3926dda/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00005-2474776497.png)


```
cyberpunk, long hair, red eyes,
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2474776497, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: depth_midas, Model: control_v11f1p_sd15_depth [cfd03158], Weight: 1, Resize Mode: Crop and Resize, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: 1.8.0-RC

```

# OpenPose 테스트
---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/af62b43aea8453bb53381fcb2a90c8a083a2a5bc/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/pose-fighting-full-009-ar2x3.png)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/af62b43aea8453bb53381fcb2a90c8a083a2a5bc/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00006-2269667599.png)


# Pixelize 테스트
---
![image](https://raw.githubusercontent.com/ReeELL/AI_Project/9affc66665c38e52a305a60e18f4335102de80db/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(1).jpg)

![image](https://raw.githubusercontent.com/ReeELL/AI_Project/9affc66665c38e52a305a60e18f4335102de80db/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00002.png)


# Manual provisioning

## Diffusion_models (fp16)

```bash
huggingface-cli download  Comfy-Org/Wan_2.1_ComfyUI_repackaged split_files/diffusion_models/wan2.1_t2v_14B_fp16.safetensors \
--local-dir /workspace/ComfyUI/models/diffusion_models/

huggingface-cli download Comfy-Org/Wan_2.1_ComfyUI_repackaged split_files/diffusion_models/wan2.1_i2v_720p_14B_fp16.safetensors \
--local-dir /workspace/ComfyUI/models/diffusion_models/
```

## Text Encoder (fp8 and fp16)

```bash
huggingface-cli download Comfy-Org/Wan_2.1_ComfyUI_repackaged split_files/text_encoders/umt5_xxl_fp8_e4m3fn_scaled.safetensors \
--local-dir /workspace/ComfyUI/models/text_encoders/

huggingface-cli download Comfy-Org/Wan_2.1_ComfyUI_repackaged split_files/text_encoders/umt5_xxl_fp16.safetensors \
--local-dir /workspace/ComfyUI/models/text_encoders/
```

## Vae

```bash
huggingface-cli download Comfy-Org/Wan_2.1_ComfyUI_repackaged split_files/vae/wan_2.1_vae.safetensors \
--local-dir /workspace/ComfyUI/models/vae/
```

## Upscale_models copied to LS110824

```bash
huggingface-cli download LS110824/upscale RealESRGAN_x2plus.pth \
--local-dir /workspace/ComfyUI/models/upscale_models/

huggingface-cli download LS110824/upscale 4x_foolhardy_Remacri.pth \
--local-dir /workspace/ComfyUI/models/upscale_models/
```


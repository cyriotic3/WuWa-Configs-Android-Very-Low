based on AlteriaX's Android-Low config, made values lower/higher by 50%

move both these files to:

/storage/emulated/0/Android/data/com.kurogame.wutheringwaves.global/files/UE4Game/Client/

require access to android/data, figure that out yourself.

---

Commands not included in config that might be useful:
```
Place commands in Engine.ini
Under [/Script/Engine.RendererSettings]

; enables Vulkan API
r.Android.DisableVulkanSupport=0
r.Vulkan.RobustBufferAccess=0
r.Vulkan.DescriptorSetLayoutMode=0

; 0: Disable | 1: Enable
; Lowers FPS to 30 when CPU temp over 65°C
r.Kuro.AutoCoolEnable=1
```

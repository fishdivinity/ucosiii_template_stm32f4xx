# This a ucosiii Template

Download and use this to add personalization code

RTE_Components.h is stm32f4xx



!!! Support VS Code for writing

 [./.vscode/c_cpp_properties.json](./.vscode/c_cpp_properties.json)  	Please modify it according to your Keil environment

```json
{
    "configurations": [
        {
            "name": "Template",
            "includePath": [
                "c:/Keil_v5/ARM/Pack/Keil/STM32F4xx_DFP/1.0.8/Device/Include",
                "c:/Keil_v5/ARM/Pack/ARM/CMSIS/4.2.0/CMSIS/Include",
                "c:/Keil_v5/ARM/Pack/ARM/CMSIS/4.2.0/CMSIS/Driver/Include",
                "c:/Keil_v5/ARM/Pack/Keil/STM32F4xx_DFP/1.0.8/Device/StdPeriph_Driver/inc",
                "c:/Keil_v5/ARM/Pack/Keil/STM32F4xx_DFP/1.0.8/Device/StdPeriph_Driver/templates",
                "${workspaceFolder}/CORE",
                "${workspaceFolder}/SYSTEM/delay",
                "${workspaceFolder}/SYSTEM/sys",
                "${workspaceFolder}/SYSTEM/usart",
                "${workspaceFolder}/FWLIB/STM32F4xx_StdPeriph_Driver/inc",
                "${workspaceFolder}/USER",
                "${workspaceFolder}/HARDWARE/LED",
                "${workspaceFolder}/UCOSIII/uC-CPU",
                "${workspaceFolder}/UCOSIII/uC-LIB",
                "${workspaceFolder}/UCOSIII/uCOS-III",
                "${workspaceFolder}/UCOSIII/UCOS_BSP",
                "${workspaceFolder}/UCOSIII/uCOS_CONFIG",
                "${workspaceFolder}/UCOSIII/uCOS-III/Source",
                "${workspaceFolder}/UCOSIII/uC-CPU/ARM-Cortex-M4/RealView",
                "${workspaceFolder}/UCOSIII/uC-LIB/Ports/ARM-Cortex-M4/RealView",
                "${workspaceFolder}/UCOSIII/uCOS-III/Ports/ARM-Cortex-M4/Generic/RealView",
                "c:/Keil_v5/ARM/ARMCC/include",
                "c:/Keil_v5/ARM/ARMCC/include/rw",
                "${workspaceFolder}/FWLIB/STM32F4xx_StdPeriph_Driver/src"
            ],
            "defines": [
                "STM32F40_41xxx",
                "USE_STDPERIPH_DRIVER",
                "__FPU_USED=1",
                "__CC_ARM",
                "__arm__",
                "__align(x)=",
                "__ALIGNOF__(x)=",
                "__alignof__(x)=",
                "__asm(x)=",
                "__forceinline=",
                "__restrict=",
                "__global_reg(n)=",
                "__inline=",
                "__int64=long long",
                "__INTADDR__(expr)=0",
                "__irq=",
                "__packed=",
                "__pure=",
                "__smc(n)=",
                "__svc(n)=",
                "__svc_indirect(n)=",
                "__svc_indirect_r7(n)=",
                "__value_in_regs=",
                "__weak=",
                "__writeonly=",
                "__declspec(x)=",
                "__attribute__(x)=",
                "__nonnull__(x)=",
                "__register=",
                "__breakpoint(x)=",
                "__cdp(x,y,z)=",
                "__clrex()=",
                "__clz(x)=0U",
                "__current_pc()=0U",
                "__current_sp()=0U",
                "__disable_fiq()=",
                "__disable_irq()=",
                "__dmb(x)=",
                "__dsb(x)=",
                "__enable_fiq()=",
                "__enable_irq()=",
                "__fabs(x)=0.0",
                "__fabsf(x)=0.0f",
                "__force_loads()=",
                "__force_stores()=",
                "__isb(x)=",
                "__ldrex(x)=0U",
                "__ldrexd(x)=0U",
                "__ldrt(x)=0U",
                "__memory_changed()=",
                "__nop()=",
                "__pld(...)=",
                "__pli(...)=",
                "__qadd(x,y)=0",
                "__qdbl(x)=0",
                "__qsub(x,y)=0",
                "__rbit(x)=0U",
                "__rev(x)=0U",
                "__return_address()=0U",
                "__ror(x,y)=0U",
                "__schedule_barrier()=",
                "__semihost(x,y)=0",
                "__sev()=",
                "__sqrt(x)=0.0",
                "__sqrtf(x)=0.0f",
                "__ssat(x,y)=0",
                "__strex(x,y)=0U",
                "__strexd(x,y)=0",
                "__strt(x,y)=",
                "__swp(x,y)=0U",
                "__usat(x,y)=0U",
                "__wfe()=",
                "__wfi()=",
                "__yield()=",
                "__vfp_status(x,y)=0"
            ],
            "intelliSenseMode": "${default}"
        }
    ],
    "version": 4
}
```

### If your Keil is not installed on C disk, please modify the configuration of Keil in JSON.


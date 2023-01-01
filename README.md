# VulkanDiagram
Visual study aid to help build mental map of the Vulkan structures, functions, and enums.

[Vulkan](https://www.vulkan.org/) is a clean GPU API in C, but it has many functions, structures, and enums, whose dependencies are intricately interconnected.
Unless you are a prodigy with some photographic memory, it is difficult to keep track of all the necessary elements in the brain.
This set of diagrams is intended to be a visual aid to grasp the intricacy and interconnectivity of the Vulkan API easily.
This is by no means comprehensive, and I'm still learning, but it covers the basic elements for rendering.

<a href="individual_pages/overview.pdf"> <img src="individual_pages/overview.png" height="80"/></a>
<a href="individual_pages/glfw.pdf"> <img src="individual_pages/glfw.png" height="80"/></a>
<a href="individual_pages/vkinstance.pdf"> <img src="individual_pages/vkinstance.png" height="80"/></a>
<a href="individual_pages/vksurface.pdf"> <img src="individual_pages/vksurface.png" height="80"/></a>
<a href="individual_pages/vkphysicaldevice.pdf"> <img src="individual_pages/vkphysicaldevice.png" height="80"/></a>
<a href="individual_pages/vkphysicaldeviceproperties.pdf"> <img src="individual_pages/vkphysicaldeviceproperties.png" height="80"/></a>
<a href="individual_pages/vkphysicaldevicememoryproperties.pdf"> <img src="individual_pages/vkphysicaldevicememoryproperties.png" height="80"/></a>
<a href="individual_pages/vkdevice_vkqueue.pdf"> <img src="individual_pages/vkdevice_vkqueue.png" height="80"/></a>
<a href="individual_pages/vkgetphysicaldevicesurfacesupportkhr.pdf"> <img src="individual_pages/vkgetphysicaldevicesurfacesupportkhr.png" height="80"/></a>
<a href="individual_pages/vkswapchainkhr.pdf"> <img src="individual_pages/vkswapchainkhr.png" height="80"/></a>
<a href="individual_pages/vksubpassdescription.pdf"> <img src="individual_pages/vksubpassdescription.png" height="80"/></a>
<a href="individual_pages/vkattachmentdescription.pdf"> <img src="individual_pages/vkattachmentdescription.png" height="80"/></a>
<a href="individual_pages/vkdevicememory.pdf"> <img src="individual_pages/vkdevicememory.png" height="80"/></a>
<a href="individual_pages/vkbuffer.pdf"> <img src="individual_pages/vkbuffer.png" height="80"/></a>
<a href="individual_pages/vksampler.pdf"> <img src="individual_pages/vksampler.png" height="80"/></a>
<a href="individual_pages/vkimage.pdf"> <img src="individual_pages/vkimage.png" height="80"/></a>
<a href="individual_pages/vkimageview.pdf"> <img src="individual_pages/vkimageview.png" height="80"/></a>
<a href="individual_pages/vkframebuffer.pdf"> <img src="individual_pages/vkframebuffer.png" height="80"/></a>
<a href="individual_pages/vkcommandpool.pdf"> <img src="individual_pages/vkcommandpool.png" height="80"/></a>
<a href="individual_pages/vkdescriptorsetlayout.pdf"> <img src="individual_pages/vkdescriptorsetlayout.png" height="80"/></a>
<a href="individual_pages/vkdescriptorpool.pdf"> <img src="individual_pages/vkdescriptorpool.png" height="80"/></a>
<a href="individual_pages/vkdescriptorset.pdf"> <img src="individual_pages/vkdescriptorset.png" height="80"/></a>
<a href="individual_pages/vksemaphore.pdf"> <img src="individual_pages/vksemaphore.png" height="80"/></a>
<a href="individual_pages/vkpipelinelayout.pdf"> <img src="individual_pages/vkpipelinelayout.png" height="80"/></a>
<a href="individual_pages/vkpipelineshaderstagecreateinfo.pdf"> <img src="individual_pages/vkpipelineshaderstagecreateinfo.png" height="80"/></a>
<a href="individual_pages/vkpipelineinputassemblystatecreateinfo.pdf"> <img src="individual_pages/vkpipelineinputassemblystatecreateinfo.png" height="80"/></a>
<a href="individual_pages/vkpipelinemultisamplestatecreateinfo.pdf"> <img src="individual_pages/vkpipelinemultisamplestatecreateinfo.png" height="80"/></a>
<a href="individual_pages/vkpipelinecolorblendstatecreateinfo.pdf"> <img src="individual_pages/vkpipelinecolorblendstatecreateinfo.png" height="80"/></a>
<a href="individual_pages/vkpipeline.pdf"> <img src="individual_pages/vkpipeline.png" height="80"/></a>
<a href="individual_pages/outermostloop.pdf"> <img src="individual_pages/outermostloop.png" height="80"/></a>
<a href="individual_pages/midlooppercommandbuffer.pdf"> <img src="individual_pages/midlooppercommandbuffer.png" height="80"/></a>
<a href="individual_pages/innermostloopperrenderpass.pdf"> <img src="individual_pages/innermostloopperrenderpass.png" height="80"/></a>
<a href="individual_pages/vkcommandbufferforaonetimecommand.pdf"> <img src="individual_pages/vkcommandbufferforaonetimecommand.png" height="80"/></a>
<a href="individual_pages/onetimecommandforcopying.pdf"> <img src="individual_pages/onetimecommandforcopying.png" height="80"/></a>
<a href="individual_pages/memorybarrier.pdf"> <img src="individual_pages/memorybarrier.png" height="80"/></a>


All the pages in a single PDF file is found in [vulkan_diagrams.pdf](vulkan_diagrams.pdf).


## Overview
An overview of some important elements and their interdependencies for very basic rendering.

<a href="individual_pages/overview.pdf"> <img src="individual_pages/overview.png" height="200"/></a>

## GLFW
GLFW is not part of Vulkan, but it is frequently used in samples & tutorials.
It is good to know how Vulkan interacts with the window management.

<a href="individual_pages/glfw.pdf"> <img src="individual_pages/glfw.png" height="200"/></a>

## VkInstance

<a href="individual_pages/vkinstance.pdf"> <img src="individual_pages/vkinstance.png" height="200"/></a>

## VkSurface
For Xwindow systems.

<a href="individual_pages/vksurface.pdf"> <img src="individual_pages/vksurface.png" height="200"/></a>

## VkPhysicalDevice, VkExtensionProperties, VkSurfaceCapabilitiesKHR, VkSurfaceFormatKHR, & VkPresentModeKHR
With some sample outputs from a computer with NVIDIA Geforce RTX 3060 8GB.

<a href="individual_pages/vkphysicaldevice.pdf"> <img src="individual_pages/vkphysicaldevice.png" height="200"/></a>

## VkPhysicalDeviceProperties & VkPhysicalDeviceFeatures
With some sample outputs from NVIDIA Geforce RTX 3060 8GB.

<a href="individual_pages/vkphysicaldeviceproperties.pdf"> <img src="individual_pages/vkphysicaldeviceproperties.png" height="200"/></a>

## VkPhysicalDeviceMemoryProperties
With some sample outputs from NVIDIA Geforce RTX 3060 8GB.

<a href="individual_pages/vkphysicaldevicememoryproperties.pdf"> <img src="individual_pages/vkphysicaldevicememoryproperties.png" height="200"/></a>

## VkDevice & VkQueue
With some sample outputs for VkQueueFamilyProperties from NVIDIA Geforce RTX 3060 8GB.

<a href="individual_pages/vkdevice_vkqueue.pdf"> <img src="individual_pages/vkdevice_vkqueue.png" height="200"/></a>

## vkGetPhysicalDeviceSurfaceSupportKHR(), vkGetPhysicalDeviceSurfaceCapabilitiesKHR(), vkGetPhysicalDeviceSurfacePresentModesKHR(), and vkGetPhysicalDeviceSurfaceFormatsKHR() for VkSwapchainKHR

<a href="individual_pages/vkgetphysicaldevicesurfacesupportkhr.pdf"> <img src="individual_pages/vkgetphysicaldevicesurfacesupportkhr.png" height="200"/></a>

## VkSwapchainKHR

<a href="individual_pages/vkswapchainkhr.pdf"> <img src="individual_pages/vkswapchainkhr.png" height="200"/></a>

## VkSubpassDescription & VkSubpassDependency for VkRenderPass

<a href="individual_pages/vksubpassdescription.pdf"> <img src="individual_pages/vksubpassdescription.png" height="200"/></a>

## VkAttachmentDescription & VkRenderPass

<a href="individual_pages/vkattachmentdescription.pdf"> <img src="individual_pages/vkattachmentdescription.png" height="200"/></a>

## VkDeviceMemory

<a href="individual_pages/vkdevicememory.pdf"> <img src="individual_pages/vkdevicememory.png" height="200"/></a>

## VkBuffer

<a href="individual_pages/vkbuffer.pdf"> <img src="individual_pages/vkbuffer.png" height="200"/></a>

## VkSampler

<a href="individual_pages/vksampler.pdf"> <img src="individual_pages/vksampler.png" height="200"/></a>

## VkImage

<a href="individual_pages/vkimage.pdf"> <img src="individual_pages/vkimage.png" height="200"/></a>

## VkImageView

<a href="individual_pages/vkimageview.pdf"> <img src="individual_pages/vkimageview.png" height="200"/></a>

## VkFramebuffer

<a href="individual_pages/vkframebuffer.pdf"> <img src="individual_pages/vkframebuffer.png" height="200"/></a>

## VkCommandPool & VkCommandBuffer

<a href="individual_pages/vkcommandpool.pdf"> <img src="individual_pages/vkcommandpool.png" height="200"/></a>

## VkDescriptorSetLayout

<a href="individual_pages/vkdescriptorsetlayout.pdf"> <img src="individual_pages/vkdescriptorsetlayout.png" height="200"/></a>

## VkDescriptorPool

<a href="individual_pages/vkdescriptorpool.pdf"> <img src="individual_pages/vkdescriptorpool.png" height="200"/></a>

## VkDescriptorSet

<a href="individual_pages/vkdescriptorset.pdf"> <img src="individual_pages/vkdescriptorset.png" height="200"/></a>

## VkSemaphore & VkFence

<a href="individual_pages/vksemaphore.pdf"> <img src="individual_pages/vksemaphore.png" height="200"/></a>

## VkPipelineLayout for VkGraphicsPipelineCreateInfo & vkCmdBindDescriptorSets()

<a href="individual_pages/vkpipelinelayout.pdf"> <img src="individual_pages/vkpipelinelayout.png" height="200"/></a>

## VkPipelineShaderStageCreateInfo & VkPipelineVertexInputStateCreateInfo for VkGraphicsPipelineCreateInfo

<a href="individual_pages/vkpipelineshaderstagecreateinfo.pdf"> <img src="individual_pages/vkpipelineshaderstagecreateinfo.png" height="200"/></a>

## VkPipelineInputAssemblyStateCreateInfo, VkPipelineTessellationStateCreateInfo, VkPipelineViewportStateCreateInfo, and VkPipelineRasterizationStateCreateInfo for VkGraphicsPipelineCreateInfo

<a href="individual_pages/vkpipelineinputassemblystatecreateinfo.pdf"> <img src="individual_pages/vkpipelineinputassemblystatecreateinfo.png" height="200"/></a>

## VkPipelineMultisampleStateCreateInfo & VkPipelineDepthStencilStateCreateInfo for VkGraphicsPipelineCreateInfo

<a href="individual_pages/vkpipelinemultisamplestatecreateinfo.pdf"> <img src="individual_pages/vkpipelinemultisamplestatecreateinfo.png" height="200"/></a>

## VkPipelineColorBlendStateCreateInfo & VkPipelineDynamicStateCreateInfo for VkGraphicsPipelineCreateInfo

<a href="individual_pages/vkpipelinecolorblendstatecreateinfo.pdf"> <img src="individual_pages/vkpipelinecolorblendstatecreateinfo.png" height="200"/></a>

## VkPipeline

<a href="individual_pages/vkpipeline.pdf"> <img src="individual_pages/vkpipeline.png" height="200"/></a>

## Outermost Loop per Frame

<a href="individual_pages/outermostloop.pdf"> <img src="individual_pages/outermostloop.png" height="200"/></a>

## Mid Loop per CommandBuffer

<a href="individual_pages/midlooppercommandbuffer.pdf"> <img src="individual_pages/midlooppercommandbuffer.png" height="200"/></a>

## Innermost Loop per RenderPass
Actually it consits of further two leavels: Outer per Renderpass, and Inner per Pipeline(subpass).

<a href="individual_pages/innermostloopperrenderpass.pdf"> <img src="individual_pages/innermostloopperrenderpass.png" height="200"/></a>

## VkCommandBuffer for a One-Time Command

<a href="individual_pages/vkcommandbufferforaonetimecommand.pdf"> <img src="individual_pages/vkcommandbufferforaonetimecommand.png" height="200"/></a>

## One-Time Command for Copying with vkCmdCopyBuffer(), vkCmdCopyBufferToImage(), vkCmdCopyBufferToImage(), and vkCmdBlitImage()

<a href="individual_pages/onetimecommandforcopying.pdf"> <img src="individual_pages/onetimecommandforcopying.png" height="200"/></a>

## MemoryBarrier

<a href="individual_pages/memorybarrier.pdf"> <img src="individual_pages/memorybarrier.png" height="200"/></a>

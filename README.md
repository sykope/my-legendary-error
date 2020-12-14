0016:err:ntoskrnl:ZwLoadDriver failed to create driver L"\\Registry\\Machine\\System\\CurrentControlSet\\Services\\NDIS": 00000001
info:  Game: Launcher.exe
info:  DXVK: v1.7.3-4-g03f11baf
info:  Built-in extension providers:
info:    Win32 WSI
info:    OpenVR
warn:  OpenVR: Failed to locate module
info:  Enabled instance extensions:
info:    VK_KHR_surface
info:    VK_KHR_win32_surface
WARNING: radv is not a conformant vulkan implementation, testing use only.
WARNING: radv is not a conformant vulkan implementation, testing use only.
warn:  D3D9: VK_FORMAT_D24_UNORM_S8_UINT -> VK_FORMAT_D32_SFLOAT_S8_UINT
info:  AMD RADV PITCAIRN (ACO):
info:    Driver: 20.99.99
info:    Vulkan: 1.2.145
info:    Memory Heap[0]: 
info:      Size: 768 MiB
info:      Flags: 0x1
info:      Memory Type[0]: Property Flags = 0x1
info:    Memory Heap[1]: 
info:      Size: 3072 MiB
info:      Flags: 0x0
info:      Memory Type[1]: Property Flags = 0x6
info:      Memory Type[3]: Property Flags = 0xe
info:    Memory Heap[2]: 
info:      Size: 256 MiB
info:      Flags: 0x1
info:      Memory Type[2]: Property Flags = 0x7
info:  Process set as DPI aware
info:  Adapter LUID 0: 0:3f4
info:  Device properties:
info:    Device name:     : AMD RADV PITCAIRN (ACO)
info:    Driver version   : 20.99.99
info:  Enabled device extensions:
info:    VK_AMD_memory_overallocation_behavior
info:    VK_AMD_shader_fragment_mask
info:    VK_EXT_depth_clip_enable
info:    VK_EXT_host_query_reset
info:    VK_EXT_memory_priority
info:    VK_EXT_shader_demote_to_helper_invocation
info:    VK_EXT_shader_stencil_export
info:    VK_EXT_shader_viewport_index_layer
info:    VK_EXT_transform_feedback
info:    VK_EXT_vertex_attribute_divisor
info:    VK_KHR_create_renderpass2
info:    VK_KHR_depth_stencil_resolve
info:    VK_KHR_draw_indirect_count
info:    VK_KHR_driver_properties
info:    VK_KHR_image_format_list
info:    VK_KHR_sampler_mirror_clamp_to_edge
info:    VK_KHR_swapchain
info:  Device features:
info:    robustBufferAccess                     : 1
info:    fullDrawIndexUint32                    : 1
info:    imageCubeArray                         : 1
info:    independentBlend                       : 1
info:    geometryShader                         : 1
info:    tessellationShader                     : 0
info:    sampleRateShading                      : 1
info:    dualSrcBlend                           : 0
info:    logicOp                                : 0
info:    multiDrawIndirect                      : 0
info:    drawIndirectFirstInstance              : 0
info:    depthClamp                             : 1
info:    depthBiasClamp                         : 1
info:    fillModeNonSolid                       : 1
info:    depthBounds                            : 1
info:    multiViewport                          : 1
info:    samplerAnisotropy                      : 1
info:    textureCompressionBC                   : 1
info:    occlusionQueryPrecise                  : 1
info:    pipelineStatisticsQuery                : 1
info:    vertexPipelineStoresAndAtomics         : 1
info:    fragmentStoresAndAtomics               : 0
info:    shaderImageGatherExtended              : 0
info:    shaderStorageImageExtendedFormats      : 1
info:    shaderStorageImageReadWithoutFormat    : 0
info:    shaderStorageImageWriteWithoutFormat   : 1
info:    shaderClipDistance                     : 1
info:    shaderCullDistance                     : 1
info:    shaderFloat64                          : 0
info:    shaderInt64                            : 0
info:    variableMultisampleRate                : 0
info:  VK_EXT_4444_formats
info:    formatA4R4G4B4                         : 0
info:    formatA4B4G4R4                         : 0
info:  VK_EXT_custom_border_color
info:    customBorderColors                     : 0
info:    customBorderColorWithoutFormat         : 0
info:  VK_EXT_depth_clip_enable
info:    depthClipEnable                        : 1
info:  VK_EXT_extended_dynamic_state
info:    extendedDynamicState                   : 0
info:  VK_EXT_host_query_reset
info:    hostQueryReset                         : 1
info:  VK_EXT_memory_priority
info:    memoryPriority                         : 1
info:  VK_EXT_robustness2
info:    robustBufferAccess2                    : 0
info:    robustImageAccess2                     : 0
info:    nullDescriptor                         : 0
info:  VK_EXT_shader_demote_to_helper_invocation
info:    shaderDemoteToHelperInvocation         : 1
info:  VK_EXT_transform_feedback
info:    transformFeedback                      : 0
info:    geometryStreams                        : 0
info:  VK_EXT_vertex_attribute_divisor
info:    vertexAttributeInstanceRateDivisor     : 1
info:    vertexAttributeInstanceRateZeroDivisor : 1
info:  Queue families:
info:    Graphics : 0
info:    Transfer : 1
warn:  DXVK: No state cache file found
warn:  DXVK: Creating new state cache file
info:  DXVK: Using 3 compiler threads
info:  D3D9DeviceEx::ResetSwapChain:
info:    Requested Presentation Parameters
info:      - Width:              1
info:      - Height:             1
info:      - Format:             D3D9Format::A8R8G8B8
info:      - Auto Depth Stencil: false
info:                  ^ Format: D3D9Format::Unknown
info:      - Windowed:           true
warn:  winevulkan detected, disabling exclusive fullscreen support
info:  Presenter: Actual swap chain properties:
info:    Format:       VK_FORMAT_B8G8R8A8_UNORM
info:    Present mode: VK_PRESENT_MODE_IMMEDIATE_KHR
info:    Buffer size:  849x616
info:    Image count:  3
info:    Exclusive FS: 0
warn:  D3D9DeviceEx::SetRenderState: Unhandled render state D3DRS_LASTPIXEL

Unhandled Exception:
System.NotImplementedException: The method or operation is not implemented.
  at MS.Internal.HRESULT.Check (System.Int32 hr) [0x00016] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.EventProxyWrapper.CreateEventProxyWrapper (System.Windows.Media.IInvokable invokable) [0x00055] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaEventsHelper.CreateMediaEventsHelper (System.Windows.Media.MediaPlayer mediaPlayer, System.Windows.Media.MediaEventsHelper& eventsHelper, System.Windows.Media.SafeMILHandle& unmanagedProxy) [0x00009] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayerState.CreateMedia (System.Windows.Media.MediaPlayer mediaPlayer) [0x00003] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayerState..ctor (System.Windows.Media.MediaPlayer mediaPlayer) [0x0003f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.EnsureState () [0x0000f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.WritePreamble () [0x00008] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.Open (System.Uri source) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at Launcher.SoundEffect.GetEffectInstance () [0x00017] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.SoundEffect.Play () [0x0000d] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.Transition (System.Windows.FrameworkElement to, System.Windows.Media.Animation.Storyboard sbOut, System.Windows.Media.Animation.Storyboard sbIn) [0x0001b] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.TransitionLeft (System.Windows.FrameworkElement to) [0x00000] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.DisplayOkBox (System.String Message) [0x00052] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.wndMain_Loaded (System.Object sender, System.Windows.RoutedEventArgs e) [0x0009c] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at System.Windows.RoutedEventHandlerInfo.InvokeHandler (System.Object target, System.Windows.RoutedEventArgs routedEventArgs) [0x0002a] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.RouteItem.InvokeHandler (System.Windows.RoutedEventArgs routedEventArgs) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.EventRoute.InvokeHandlersImpl (System.Object source, System.Windows.RoutedEventArgs args, System.Boolean reRaised) [0x00137] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.EventRoute.InvokeHandlers (System.Object source, System.Windows.RoutedEventArgs args) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.UIElement.RaiseEventImpl (System.Windows.DependencyObject sender, System.Windows.RoutedEventArgs args) [0x00060] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.UIElement.RaiseEvent (System.Windows.RoutedEventArgs e) [0x0001c] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.FrameworkElement.OnLoaded (System.Windows.RoutedEventArgs args) [0x00001] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at MS.Internal.FrameworkObject.OnLoaded (System.Windows.RoutedEventArgs args) [0x0000c] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastEvent (System.Windows.DependencyObject root, System.Windows.RoutedEvent routedEvent) [0x00051] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastLoadedSynchronously (System.Windows.DependencyObject rootDO, System.Boolean isLoaded) [0x0000a] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastLoadedEvent (System.Object root) [0x00028] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at MS.Internal.LoadedOrUnloadedOperation.DoWork () [0x0000f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.FireLoadedPendingCallbacks () [0x00042] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.FireInvokeOnRenderCallbacks () [0x00075] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.RenderMessageHandlerCore (System.Object resizedCompositionTarget) [0x00074] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.RenderMessageHandler (System.Object resizedCompositionTarget) [0x00033] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.Resize (System.Windows.Media.ICompositionTarget resizedCompositionTarget) [0x0003b] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndTarget.OnResize () [0x0009d] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndTarget.HandleMessage (MS.Internal.Interop.WindowMessage msg, System.IntPtr wparam, System.IntPtr lparam) [0x00388] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndSource.HwndTargetFilterMessage (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x00022] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at MS.Win32.HwndWrapper.WndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x0003a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.DispatcherCallbackOperation (System.Object o) [0x00042] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.LegacyInvokeImpl (System.Windows.Threading.DispatcherPriority priority, System.TimeSpan timeout, System.Delegate method, System.Object args, System.Int32 numArgs) [0x000fc] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Invoke (System.Windows.Threading.DispatcherPriority priority, System.Delegate method, System.Object arg) [0x00011] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.SubclassWndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam) [0x00154] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at (wrapper native-to-managed) MS.Win32.HwndSubclass.SubclassWndProc(intptr,int,intptr,intptr)
  at (wrapper managed-to-native) MS.Win32.UnsafeNativeMethods.ShowWindow(System.Runtime.InteropServices.HandleRef,int)
  at System.Windows.Window.ShowHelper (System.Object booleanBox) [0x00135] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.InvokeImpl () [0x00099] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.InvokeInSecurityContext (System.Object state) [0x00008] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Internal.CulturePreservingExecutionContext.CallbackWrapper (System.Object obj) [0x0001d] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Threading.ExecutionContext.RunInternal (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state, System.Boolean preserveSyncCtx) [0x00071] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at System.Threading.ExecutionContext.Run (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state, System.Boolean preserveSyncCtx) [0x00000] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at System.Threading.ExecutionContext.Run (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state) [0x0002b] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at MS.Internal.CulturePreservingExecutionContext.Run (MS.Internal.CulturePreservingExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state) [0x00047] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.Invoke () [0x00016] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.ProcessQueue () [0x00114] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WndProcHook (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x00061] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndWrapper.WndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x0003a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.DispatcherCallbackOperation (System.Object o) [0x00042] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.LegacyInvokeImpl (System.Windows.Threading.DispatcherPriority priority, System.TimeSpan timeout, System.Delegate method, System.Object args, System.Int32 numArgs) [0x000fc] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Invoke (System.Windows.Threading.DispatcherPriority priority, System.Delegate method, System.Object arg) [0x00011] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.SubclassWndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam) [0x00154] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at (wrapper native-to-managed) MS.Win32.HwndSubclass.SubclassWndProc(intptr,int,intptr,intptr)
  at (wrapper managed-to-native) MS.Win32.UnsafeNativeMethods.DispatchMessage(System.Windows.Interop.MSG&)
  at System.Windows.Threading.Dispatcher.TranslateAndDispatchMessage (System.Windows.Interop.MSG& msg) [0x0001a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.PushFrameImpl (System.Windows.Threading.DispatcherFrame frame) [0x0004c] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.PushFrame (System.Windows.Threading.DispatcherFrame frame) [0x00077] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Run () [0x00006] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Application.RunDispatcher (System.Object ignore) [0x00023] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.RunInternal (System.Windows.Window window) [0x0010d] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.Run (System.Windows.Window window) [0x00008] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.Run () [0x00009] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at Launcher.App.Main () [0x0000c] in <825dbbaa69904d2887b2e7172416e1c0>:0 
[ERROR] FATAL UNHANDLED EXCEPTION: System.NotImplementedException: The method or operation is not implemented.
  at MS.Internal.HRESULT.Check (System.Int32 hr) [0x00016] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.EventProxyWrapper.CreateEventProxyWrapper (System.Windows.Media.IInvokable invokable) [0x00055] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaEventsHelper.CreateMediaEventsHelper (System.Windows.Media.MediaPlayer mediaPlayer, System.Windows.Media.MediaEventsHelper& eventsHelper, System.Windows.Media.SafeMILHandle& unmanagedProxy) [0x00009] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayerState.CreateMedia (System.Windows.Media.MediaPlayer mediaPlayer) [0x00003] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayerState..ctor (System.Windows.Media.MediaPlayer mediaPlayer) [0x0003f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.EnsureState () [0x0000f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.WritePreamble () [0x00008] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaPlayer.Open (System.Uri source) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at Launcher.SoundEffect.GetEffectInstance () [0x00017] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.SoundEffect.Play () [0x0000d] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.Transition (System.Windows.FrameworkElement to, System.Windows.Media.Animation.Storyboard sbOut, System.Windows.Media.Animation.Storyboard sbIn) [0x0001b] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.TransitionLeft (System.Windows.FrameworkElement to) [0x00000] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.DisplayOkBox (System.String Message) [0x00052] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at Launcher.MainWindow.wndMain_Loaded (System.Object sender, System.Windows.RoutedEventArgs e) [0x0009c] in <825dbbaa69904d2887b2e7172416e1c0>:0 
  at System.Windows.RoutedEventHandlerInfo.InvokeHandler (System.Object target, System.Windows.RoutedEventArgs routedEventArgs) [0x0002a] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.RouteItem.InvokeHandler (System.Windows.RoutedEventArgs routedEventArgs) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.EventRoute.InvokeHandlersImpl (System.Object source, System.Windows.RoutedEventArgs args, System.Boolean reRaised) [0x00137] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.EventRoute.InvokeHandlers (System.Object source, System.Windows.RoutedEventArgs args) [0x00001] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.UIElement.RaiseEventImpl (System.Windows.DependencyObject sender, System.Windows.RoutedEventArgs args) [0x00060] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.UIElement.RaiseEvent (System.Windows.RoutedEventArgs e) [0x0001c] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.FrameworkElement.OnLoaded (System.Windows.RoutedEventArgs args) [0x00001] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at MS.Internal.FrameworkObject.OnLoaded (System.Windows.RoutedEventArgs args) [0x0000c] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastEvent (System.Windows.DependencyObject root, System.Windows.RoutedEvent routedEvent) [0x00051] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastLoadedSynchronously (System.Windows.DependencyObject rootDO, System.Boolean isLoaded) [0x0000a] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.BroadcastEventHelper.BroadcastLoadedEvent (System.Object root) [0x00028] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at MS.Internal.LoadedOrUnloadedOperation.DoWork () [0x0000f] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.FireLoadedPendingCallbacks () [0x00042] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.FireInvokeOnRenderCallbacks () [0x00075] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.RenderMessageHandlerCore (System.Object resizedCompositionTarget) [0x00074] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.RenderMessageHandler (System.Object resizedCompositionTarget) [0x00033] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Media.MediaContext.Resize (System.Windows.Media.ICompositionTarget resizedCompositionTarget) [0x0003b] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndTarget.OnResize () [0x0009d] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndTarget.HandleMessage (MS.Internal.Interop.WindowMessage msg, System.IntPtr wparam, System.IntPtr lparam) [0x00388] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at System.Windows.Interop.HwndSource.HwndTargetFilterMessage (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x00022] in <d2d3da73e2ac4484b5ea094fbd571d52>:0 
  at MS.Win32.HwndWrapper.WndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x0003a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.DispatcherCallbackOperation (System.Object o) [0x00042] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.LegacyInvokeImpl (System.Windows.Threading.DispatcherPriority priority, System.TimeSpan timeout, System.Delegate method, System.Object args, System.Int32 numArgs) [0x000fc] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Invoke (System.Windows.Threading.DispatcherPriority priority, System.Delegate method, System.Object arg) [0x00011] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.SubclassWndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam) [0x00154] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at (wrapper native-to-managed) MS.Win32.HwndSubclass.SubclassWndProc(intptr,int,intptr,intptr)
  at (wrapper managed-to-native) MS.Win32.UnsafeNativeMethods.ShowWindow(System.Runtime.InteropServices.HandleRef,int)
  at System.Windows.Window.ShowHelper (System.Object booleanBox) [0x00135] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.InvokeImpl () [0x00099] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.InvokeInSecurityContext (System.Object state) [0x00008] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Internal.CulturePreservingExecutionContext.CallbackWrapper (System.Object obj) [0x0001d] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Threading.ExecutionContext.RunInternal (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state, System.Boolean preserveSyncCtx) [0x00071] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at System.Threading.ExecutionContext.Run (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state, System.Boolean preserveSyncCtx) [0x00000] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at System.Threading.ExecutionContext.Run (System.Threading.ExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state) [0x0002b] in <7713cb95b33244ed9608bf0b23fbdce9>:0 
  at MS.Internal.CulturePreservingExecutionContext.Run (MS.Internal.CulturePreservingExecutionContext executionContext, System.Threading.ContextCallback callback, System.Object state) [0x00047] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.DispatcherOperation.Invoke () [0x00016] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.ProcessQueue () [0x00114] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WndProcHook (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x00061] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndWrapper.WndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam, System.Boolean& handled) [0x0003a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.DispatcherCallbackOperation (System.Object o) [0x00042] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.InternalRealCall (System.Delegate callback, System.Object args, System.Int32 numArgs) [0x000c6] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.ExceptionWrapper.TryCatchWhen (System.Object source, System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00004] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.WrappedInvoke (System.Delegate callback, System.Object args, System.Int32 numArgs, System.Delegate catchHandler) [0x00001] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.LegacyInvokeImpl (System.Windows.Threading.DispatcherPriority priority, System.TimeSpan timeout, System.Delegate method, System.Object args, System.Int32 numArgs) [0x000fc] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Invoke (System.Windows.Threading.DispatcherPriority priority, System.Delegate method, System.Object arg) [0x00011] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at MS.Win32.HwndSubclass.SubclassWndProc (System.IntPtr hwnd, System.Int32 msg, System.IntPtr wParam, System.IntPtr lParam) [0x00154] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at (wrapper native-to-managed) MS.Win32.HwndSubclass.SubclassWndProc(intptr,int,intptr,intptr)
  at (wrapper managed-to-native) MS.Win32.UnsafeNativeMethods.DispatchMessage(System.Windows.Interop.MSG&)
  at System.Windows.Threading.Dispatcher.TranslateAndDispatchMessage (System.Windows.Interop.MSG& msg) [0x0001a] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.PushFrameImpl (System.Windows.Threading.DispatcherFrame frame) [0x0004c] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.PushFrame (System.Windows.Threading.DispatcherFrame frame) [0x00077] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Threading.Dispatcher.Run () [0x00006] in <98e8558d9113410bbb3b4c428ae8d5ce>:0 
  at System.Windows.Application.RunDispatcher (System.Object ignore) [0x00023] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.RunInternal (System.Windows.Window window) [0x0010d] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.Run (System.Windows.Window window) [0x00008] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at System.Windows.Application.Run () [0x00009] in <251e6bab7bce4da9b7717a1245189e5a>:0 
  at Launcher.App.Main () [0x0000c] in <825dbbaa69904d2887b2e7172416e1c0>:0 Cannot load assembly mscorlib
0009:err:mscoree:RuntimeHost_ExitProcess Process should have exited
0009:err:mscoree:expect_no_runtimes Process exited with a Mono runtime loaded.

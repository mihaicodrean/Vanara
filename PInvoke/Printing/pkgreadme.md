﻿![Vanara](https://github.com/dahall/Vanara/raw/master/docs/icons/VanaraHeading.png)
### Vanara.PInvoke.Printing NuGet Package
[![Version](https://img.shields.io/nuget/v/Vanara.PInvoke.Printing?label=NuGet&style=flat-square)](https://github.com/dahall/Vanara/releases)
[![Build status](https://img.shields.io/appveyor/build/dahall/vanara?label=AppVeyor%20build&style=flat-square)](https://ci.appveyor.com/project/dahall/vanara)

PInvoke API (methods, structures and constants) imported from Windows winspool.drv and prntvpt.dll.

### What is Vanara?

[Vanara](https://github.com/dahall/Vanara) is a community project that contains various .NET assemblies which have P/Invoke functions, interfaces, enums and structures from Windows libraries. Each assembly is associated with one or a few tightly related libraries.

### Issues?

First check if it's already fixed by trying the [AppVeyor build](https://ci.appveyor.com/nuget/vanara-prerelease).
If you're still running into problems, file an [issue](https://github.com/dahall/Vanara/issues).

### Included in Vanara.PInvoke.Printing

Functions | Enumerations | Structures | Interfaces
--- | --- | --- | ---
AbortPrinter<br>AddForm<br>AddJob<br>AddMonitor<br>AddPort<br>AddPrinter<br>AddPrinterConnection<br>AddPrinterConnection2<br>AddPrinterDriver<br>AddPrinterDriverEx<br>AddPrintProcessor<br>AddPrintProvidor<br>AdvancedDocumentProperties<br>BindPTProviderThunkA<br>BindPTProviderThunkW<br>ClosePrinter<br>CloseSpoolFileHandle<br>CommitSpoolData<br>ConfigurePort<br>ConnectToPrinterDlg<br>ConvertDevModeToPrintTicketThunk2<br>ConvertPrintTicketToDevModeThunk2<br>CorePrinterDriverInstalled<br>DeleteForm<br>DeleteMonitor<br>DeletePort<br>DeletePrinter<br>DeletePrinterConnection<br>DeletePrinterData<br>DeletePrinterDataEx<br>DeletePrinterDriver<br>DeletePrinterDriverEx<br>DeletePrinterDriverPackage<br>DeletePrinterKey<br>DeletePrintProcessor<br>DeletePrintProvidor<br>DeviceCapabilities<br>DocumentEventA<br>DocumentEventW<br>DocumentProperties<br>EndDocPrinter<br>EndPagePrinter<br>EnumForms<br>EnumJobs<br>EnumMonitors<br>EnumPorts<br>EnumPrinterData<br>EnumPrinterDataEx<br>EnumPrinterDrivers<br>EnumPrinterKey<br>EnumPrinters<br>EnumPrintProcessorDatatypes<br>EnumPrintProcessors<br>FindClosePrinterChangeNotification<br>FindFirstPrinterChangeNotification<br>FindNextPrinterChangeNotification<br>FlushPrinter<br>FreePrinterNotifyInfo<br>GetCorePrinterDrivers<br>GetDefaultPrinter<br>GetForm<br>GetJob<br>GetPrintCapabilitiesThunk2<br>GetPrinter<br>GetPrinterData<br>GetPrinterDataEx<br>GetPrinterDriver<br>GetPrinterDriver2<br>GetPrinterDriverDirectory<br>GetPrinterDriverPackagePath<br>GetPrintExecutionData<br>GetPrintProcessorDirectory<br>GetSpoolFileHandle<br>InstallPrinterDriverFromPackage<br>IsValidDevmode<br>MergeAndValidatePrintTicketThunk2<br>OpenPrinter<br>OpenPrinter2<br>PrinterProperties<br>PTCloseProvider<br>PTConvertDevModeToPrintTicket<br>PTConvertPrintTicketToDevMode<br>PTGetPrintCapabilities<br>PTGetPrintDeviceCapabilities<br>PTGetPrintDeviceResources<br>PTMergeAndValidatePrintTicket<br>PTOpenProvider<br>PTOpenProviderEx<br>PTQuerySchemaVersionSupport<br>PTReleaseMemory<br>ReadPrinter<br>ReportJobProcessingProgress<br>ResetPrinter<br>ScheduleJob<br>SetDefaultPrinter<br>SetForm<br>SetJob<br>SetPort<br>SetPrinter<br>SetPrinterData<br>SetPrinterDataEx<br>StartDocPrinter<br>StartPagePrinter<br>StartXpsPrintJob<br>StartXpsPrintJob1<br>UnbindPTProviderThunk<br>UploadPrinterDriverPackage<br>WritePrinter<br> | PrintDocumentPackageCompletion<br>EDefaultDevmodeType<br>EPrintTicketScope<br>APD<br>DPD<br>UPDP<br>AccessRights<br>DC<br>DM<br>DOCUMENTEVENT<br>DSPRINT<br>EPrintPropertyType<br>EPrintXPSJobOperation<br>EPrintXPSJobProgress<br>FormFlags<br>FormStringType<br>JOB_CONTROL<br>JOB_NOTIFY_FIELD<br>JOB_PRIORITY<br>JOB_STATUS<br>NOTIFY_TYPE<br>PORT_STATUS<br>PORT_STATUS_TYPE<br>PORT_TYPE<br>PPCAPS_BORDER<br>PPCAPS_DIRECTION<br>PPCAPS_DUPLEX<br>PPCAPS_EDGE<br>PPCAPS_SCALING<br>PRINT_EXECUTION_CONTEXT<br>PRINTER_ATTRIBUTE<br>PRINTER_CHANGE<br>PRINTER_CONNECTION_FLAGS<br>PRINTER_CONTROL<br>PRINTER_ENUM<br>PRINTER_NOTIFY_CATEGORY<br>PRINTER_NOTIFY_FIELD<br>PRINTER_NOTIFY_OPTIONS_FLAG<br>PRINTER_OPTION_FLAGS<br>PRINTER_STATUS<br>PrinterDriverAttributes<br>XPS_COLOR_INTERPOLATION<br>XPS_COLOR_TYPE<br>XPS_DASH_CAP<br>XPS_DOCUMENT_TYPE<br>XPS_FILL_RULE<br>XPS_FONT_EMBEDDING<br>XPS_IMAGE_TYPE<br>XPS_INTERLEAVING<br>XPS_LINE_CAP<br>XPS_LINE_JOIN<br>XPS_OBJECT_TYPE<br>XPS_SEGMENT_STROKE_PATTERN<br>XPS_SEGMENT_TYPE<br>XPS_SPREAD_METHOD<br>XPS_STYLE_SIMULATION<br>XPS_THUMBNAIL_SIZE<br>XPS_TILE_MODE<br>XPS_JOB_COMPLETION<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> | PrintDocumentPackageStatus<br>HPTPROVIDER<br>ADDJOB_INFO_1<br>CORE_PRINTER_DRIVER<br>DATATYPES_INFO_1<br>DOC_INFO_1<br>DOC_INFO_2<br>DOC_INFO_3<br>DRIVER_INFO_1<br>DRIVER_INFO_2<br>DRIVER_INFO_3<br>DRIVER_INFO_4<br>DRIVER_INFO_5<br>DRIVER_INFO_6<br>DRIVER_INFO_8<br>FORM_INFO_1<br>FORM_INFO_2<br>HPRINTER<br>HPRINTERCHANGENOTIFICATION<br>HSPOOLFILE<br>JOB_INFO_1<br>JOB_INFO_2<br>JOB_INFO_3<br>JOB_INFO_4<br>MONITOR_INFO_1<br>MONITOR_INFO_2<br>PORT_INFO_1<br>PORT_INFO_2<br>PORT_INFO_3<br>PRINT_EXECUTION_DATA<br>PRINTER_CONNECTION_INFO_1<br>PRINTER_ENUM_VALUES<br>PRINTER_INFO_1<br>PRINTER_INFO_2<br>PRINTER_INFO_3<br>PRINTER_INFO_4<br>PRINTER_INFO_5<br>PRINTER_INFO_6<br>PRINTER_INFO_7<br>PRINTER_INFO_8<br>PRINTER_INFO_9<br>PRINTER_NOTIFY_INFO<br>PRINTER_NOTIFY_INFO_DATA<br>PRINTER_NOTIFY_OPTIONS<br>PRINTER_NOTIFY_OPTIONS_TYPE<br>PRINTER_OPTIONS<br>PRINTPROCESSOR_CAPS_1<br>PRINTPROCESSOR_CAPS_2<br>PRINTPROCESSOR_INFO_1<br>PROVIDOR_INFO_1<br>PROVIDOR_INFO_2<br>XPS_POINT<br>XPS_RECT<br>XPS_SIZE<br>XPS_COLOR<br>XPS_DASH<br>XPS_GLYPH_INDEX<br>XPS_GLYPH_MAPPING<br>XPS_MATRIX<br>XPS_JOB_STATUS<br>NOTIFYDATA<br>XPS_COLOR_TYPE_SCRGB<br>XPS_COLOR_TYPE_CONTEXT<br>XPS_COLOR_TYPE_SRGB<br>DATA<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> | IPrintDocumentPageSource<br>IPrintPreviewPageCollection<br>IPrintDocumentPackageStatusEvent<br>IPrintDocumentPackageTarget<br>IPrintDocumentPackageTargetFactory<br>IXpsOMBrush<br>IXpsOMCanvas<br>IXpsOMColorProfileResource<br>IXpsOMColorProfileResourceCollection<br>IXpsOMDashCollection<br>IXpsOMDictionary<br>IXpsOMDocumentStructureResource<br>IXpsOMFontResource<br>IXpsOMFontResourceCollection<br>IXpsOMGeometry<br>IXpsOMGeometryFigure<br>IXpsOMGeometryFigureCollection<br>IXpsOMGlyphs<br>IXpsOMGlyphsEditor<br>IXpsOMGradientBrush<br>IXpsOMGradientStop<br>IXpsOMGradientStopCollection<br>IXpsOMImageBrush<br>IXpsOMImageResource<br>IXpsOMObjectFactory<br>IXpsOMCoreProperties<br>IXpsOMDocument<br>IXpsOMDocumentCollection<br>IXpsOMDocumentSequence<br>IXpsOMPackage<br>IXpsOMPackageWriter<br>IXpsOMPage<br>IXpsOMPageReference<br>IXpsOMPageReferenceCollection<br>IXpsOMPart<br>IXpsOMPartResources<br>IXpsOMPartUriCollection<br>IXpsOMImageResourceCollection<br>IXpsOMLinearGradientBrush<br>IXpsOMMatrixTransform<br>IXpsOMNameCollection<br>IXpsOMPath<br>IXpsOMPrintTicketResource<br>IXpsOMRadialGradientBrush<br>IXpsOMRemoteDictionaryResource<br>IXpsOMRemoteDictionaryResourceCollection<br>IXpsOMResource<br>IXpsOMShareable<br>IXpsOMSignatureBlockResource<br>IXpsOMSignatureBlockResourceCollection<br>IXpsOMSolidColorBrush<br>IXpsOMStoryFragmentsResource<br>IXpsOMThumbnailGenerator<br>IXpsOMTileBrush<br>IXpsOMVisual<br>IXpsOMVisualBrush<br>IXpsOMVisualCollection<br>IXpsPrintJob<br>IXpsPrintJobStream<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
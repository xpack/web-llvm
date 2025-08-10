---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetOptions` Class



## Declaration

<div class="doxyDeclaration">
class llvm::TargetOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad0fc1de8197ddf2c49346c5d92a2bec">DisableFramePointerElim</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DisableFramePointerElim - This returns true if frame pointer elimination optimization should be disabled for the given machine function. <a href="#aad0fc1de8197ddf2c49346c5d92a2bec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56ae8efa388a7840c07b61e6a03b33e">FramePointerIsReserved</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FramePointerIsReserved - This returns true if the frame pointer must always either point to a new frame record or be un-modified in the given function. <a href="#aa56ae8efa388a7840c07b61e6a03b33e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32054a115837c426986d56d382030345">HonorSignDependentRoundingFPMath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HonorSignDependentRoundingFPMath - Return true if the codegen must assume that the rounding mode of the FPU can change from its default. <a href="#a32054a115837c426986d56d382030345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46038c2811d0b87e138a24317748729">ShouldEmitDebugEntryValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NOTE: There are targets that still do not support the debug entry values production. <a href="#af46038c2811d0b87e138a24317748729">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479c8c348a2ac67bcaf04394a8bf9bf1">setFPDenormalMode</a> (DenormalMode Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01decced737c074204373053cbf3febb">setFP32DenormalMode</a> (DenormalMode Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c31455d7fd7493c58a465fbde97bfd8">getRawFPDenormalMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1a122d0e6a6e7f72ef1d133d5c9b87">getRawFP32DenormalMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0373cdd39b42d123ca7abb351aed1be6">getDenormalMode</a> (const fltSemantics &amp;FPType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ba9a184ba490300fef429a79c1b7a7">BinutilsVersion</a> {0, 0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If greater than 0, override the default value of <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae91d11081ad021098eed1c28e67992b6">MCAsmInfo::BinutilsVersion</a>. <a href="#a46ba9a184ba490300fef429a79c1b7a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0544e2966374684ff74255e5a4290fa7">UnsafeFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UnsafeFPMath - This flag is enabled when the -enable-unsafe-fp-math flag is specified on the command line. <a href="#a0544e2966374684ff74255e5a4290fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d277b3eb8ea035973291fe90d27d280">NoInfsFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoInfsFPMath - This flag is enabled when the -enable-no-infs-fp-math flag is specified on the command line. <a href="#a4d277b3eb8ea035973291fe90d27d280">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9cc05758a26e784f7cfa554e76f175">NoNaNsFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoNaNsFPMath - This flag is enabled when the -enable-no-nans-fp-math flag is specified on the command line. <a href="#aaf9cc05758a26e784f7cfa554e76f175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af272560bf58c962e2c9e0af3e7a7c420">NoTrappingFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoTrappingFPMath - This flag is enabled when the -enable-no-trapping-fp-math is specified on the command line. <a href="#af272560bf58c962e2c9e0af3e7a7c420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb34694aa403cda58ed7eff51e0ab2d">NoSignedZerosFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoSignedZerosFPMath - This flag is enabled when the -enable-no-signed-zeros-fp-math is specified on the command line. <a href="#a7fb34694aa403cda58ed7eff51e0ab2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b45f941f3a7290a1c5f0e967df6c1c7">ApproxFuncFPMath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ApproxFuncFPMath - This flag is enabled when the -enable-approx-func-fp-math is specified on the command line. <a href="#a6b45f941f3a7290a1c5f0e967df6c1c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e1d3fd3addb834a0bd9fd8b51f56e6">EnableAIXExtendedAltivecABI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnableAIXExtendedAltivecABI - This flag returns true when -vec-extabi is specified. <a href="#a28e1d3fd3addb834a0bd9fd8b51f56e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e4acf99d3d8efecb348006b189613f">HonorSignDependentRoundingFPMathOption</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HonorSignDependentRoundingFPMath - This returns true when the -enable-sign-dependent-rounding-fp-math is specified. <a href="#a75e4acf99d3d8efecb348006b189613f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52f160f0506a9d8da975aac224fbcdbd">NoZerosInBSS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoZerosInBSS - By default some codegens place zero-initialized data to .bss section. <a href="#a52f160f0506a9d8da975aac224fbcdbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54fc81a4ef7ab96137a9b6e78fdf838">GuaranteedTailCallOpt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GuaranteedTailCallOpt - This flag is enabled when -tailcallopt is specified on the commandline. <a href="#ad54fc81a4ef7ab96137a9b6e78fdf838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3365678cbab08add568b0a7edb28fb09">StackSymbolOrdering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StackSymbolOrdering - When true, this will allow CodeGen to order the local stack symbols (for code size, code locality, or any other heuristics). <a href="#a3365678cbab08add568b0a7edb28fb09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26d50483184808463759bea1da917f8">EnableFastISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnableFastISel - This flag enables fast-path instruction selection which trades away generated code quality in favor of reducing compile time. <a href="#ab26d50483184808463759bea1da917f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfac3721300d6e685b7543011b790e4a">EnableGlobalISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnableGlobalISel - This flag enables global instruction selection. <a href="#acfac3721300d6e685b7543011b790e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af69c47ced839e86a65b94b0a33ee5c2a">GlobalISelAbortMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a790b23e61a3ec34a2910114f261e6dbe">GlobalISelAbort</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#af69c47ced839e86a65b94b0a33ee5c2aa2faec1f9f8cc7f8f40d521c4dd574f49">GlobalISelAbortMode::Enable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnableGlobalISelAbort - Control abort behaviour when global instruction selection fails to lower/select an instruction. <a href="#a790b23e61a3ec34a2910114f261e6dbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34">SwiftAsyncFramePointerMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a62a15c006f8bc55698e0bea465699">SwiftAsyncFramePointer</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Control when and how the Swift async frame pointer bit should be set. <a href="#a66a62a15c006f8bc55698e0bea465699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b75286580e4346dbc5e186baa7e6b54">UseInitArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UseInitArray - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> .init_array instead of .ctors for static constructors. <a href="#a2b75286580e4346dbc5e186baa7e6b54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36a4179451e89551b53d4649e16d37f">DisableIntegratedAS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable the integrated assembler. <a href="#af36a4179451e89551b53d4649e16d37f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb646e2505e21a891497f665187963b3">FunctionSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit functions into separate sections. <a href="#abb646e2505e21a891497f665187963b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c7f9f16d88de8a481dd162ead65c7f">DataSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit data into separate sections. <a href="#ad0c7f9f16d88de8a481dd162ead65c7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df4dc95d9e4efbb514152b5f019cd36">IgnoreXCOFFVisibility</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not emit visibility attribute for xcoff. <a href="#a7df4dc95d9e4efbb514152b5f019cd36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a43005dca46ff41b1da878c487f3edb">XCOFFTracebackTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> traceback table. <a href="#a7a43005dca46ff41b1da878c487f3edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeee4d390f75162b6cf22adb0f1fbb78">UniqueSectionNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93470bdcaa5df890c2b75fe7e9fc165b">UniqueBasicBlockSectionNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> unique names for basic block sections. <a href="#a93470bdcaa5df890c2b75fe7e9fc165b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661f99862caa07e96eaab915c23e610e">SeparateNamedSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit named sections with the same name into different sections. <a href="#a661f99862caa07e96eaab915c23e610e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae511cb5018c52294bcff10ccde3f6789">TrapUnreachable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific trap instruction for 'unreachable' IR instructions. <a href="#ae511cb5018c52294bcff10ccde3f6789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd83fce25de1ac9f6c975135a8235c22">NoTrapAfterNoreturn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not emit a trap instruction for 'unreachable' IR instructions behind noreturn calls, even if TrapUnreachable is true. <a href="#acd83fce25de1ac9f6c975135a8235c22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab5140a64e553a0cbe994b783d6d0e6">TLSSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bit size of immediate TLS offsets (0 == use the default). <a href="#aaab5140a64e553a0cbe994b783d6d0e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ba34490ccea87c934d079ca6a8d09b">EmulatedTLS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmulatedTLS - This flag enables emulated TLS model, using emutls function in the runtime library. <a href="#ae5ba34490ccea87c934d079ca6a8d09b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d23dea0bb982335578481e1f4c7fe42">EnableTLSDESC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnableTLSDESC - This flag enables TLS Descriptors. <a href="#a0d23dea0bb982335578481e1f4c7fe42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd366f946d1f11eeab165b83d98e2847">EnableIPRA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This flag enables InterProcedural <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Allocation (IPRA). <a href="#acd366f946d1f11eeab165b83d98e2847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4c8ac550351fbf544464a6a36f681e">EmitStackSizeSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit section containing metadata on function stack sizes. <a href="#a0d4c8ac550351fbf544464a6a36f681e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d006266025255e4b084b3934ed1165">EnableMachineOutliner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables the MachineOutliner pass. <a href="#a60d006266025255e4b084b3934ed1165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e7bad531953b4136544c1a93d92d75">EnableMachineFunctionSplitter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables the MachineFunctionSplitter pass. <a href="#ac4e7bad531953b4136544c1a93d92d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0dcb30ec6167a560d0a7fae85d608c">SupportsDefaultOutlining</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if the target supports default outlining behaviour. <a href="#a8a0dcb30ec6167a560d0a7fae85d608c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266f996cc26e6ff405f3d5b7bfe16516">EmitAddrsig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit address-significance table. <a href="#a266f996cc26e6ff405f3d5b7bfe16516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4602186a8472e7bff53bd7a433b521e4">BBAddrMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8">BasicBlockSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7375652c2b8022869f1a3b05440e0b43">BBSections</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a6adf97f83acf6453d4a6a4b1070f3754">BasicBlockSection::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit basic blocks into separate sections. <a href="#a7375652c2b8022869f1a3b05440e0b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d4c3547eb7f7c521500bda959e11c4">BBSectionsFuncListBuf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Buffer that contains information on sampled basic blocks and used to selectively generate basic block sections. <a href="#ab9d4c3547eb7f7c521500bda959e11c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eac77cb2f258f547232546b42dfe5c1">EmitCallSiteInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag enables call site info production. <a href="#a5eac77cb2f258f547232546b42dfe5c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a26ddab8f249e51435d733e5aa44c1c">SupportsDebugEntryValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if the target supports the debug entry values by default. <a href="#a6a26ddab8f249e51435d733e5aa44c1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5b190e844a4fe4712507277bee42ad">EnableDebugEntryValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When set to true, the EnableDebugEntryValues option forces production of debug entry values even if the target does not officially support it. <a href="#aea5b190e844a4fe4712507277bee42ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7654bf48dbcccca78653e82cee1c4d60">ValueTrackingVariableLocations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c8eedc7a0f349964f049852ff2f7db4">ForceDwarfFrameSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWARF debug frame section. <a href="#a4c8eedc7a0f349964f049852ff2f7db4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeaffd454df0057dd4a07fddfdab15ed">XRayFunctionIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit XRay <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Index section. <a href="#aeeaffd454df0057dd4a07fddfdab15ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0a6aa4b80c1d0652cce38e309bb97f">DebugStrictDwarf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When set to true, don't use DWARF extensions in later DWARF versions. <a href="#a8a0a6aa4b80c1d0652cce38e309bb97f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718e851e53ea751a7f743509f02eedb9">Hotpatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the hotpatch flag in CodeView debug. <a href="#a718e851e53ea751a7f743509f02eedb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92eafcc9e887aec1827bcb535825ecd4">PPCGenScalarMASSEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables scalar MASS conversions. <a href="#a92eafcc9e887aec1827bcb535825ecd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2600e9c715bbb82d1507e8f126afca">JMCInstrument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable JustMyCode instrumentation. <a href="#afd2600e9c715bbb82d1507e8f126afca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d282653d72393cc4bb89953aa7a3d0">EnableCFIFixup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the <a href="/web-llvm/docs/api/classes/llvm/cfifixup">CFIFixup</a> pass. <a href="#a81d282653d72393cc4bb89953aa7a3d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b873d6a142a16395fc64518f2f88db">MisExpect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When set to true, enable MisExpect Diagnostics By default, it is set to false. <a href="#a60b873d6a142a16395fc64518f2f88db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a116889d779045bd9d83925e41c86680b">XCOFFReadOnlyPointers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When set to true, const objects with relocatable address values are put into the RO data section. <a href="#a116889d779045bd9d83925e41c86680b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0931af4649b2d1dcd3771f49971740f2">VerifyArgABICompliance</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When set to true, call/return argument extensions of narrow integers are verified in the target backend if it cares about them. <a href="#a0931af4649b2d1dcd3771f49971740f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1769477c512bc934a7066b9024fb2e">StackUsageOutput</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the stack usage file (i.e., .su file) if user passes -fstack-usage. <a href="#acc1769477c512bc934a7066b9024fb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7266b0c254907d979e9b31192e3e83f">LoopAlignment</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If greater than 0, override TargetLoweringBase::PrefLoopAlignment. <a href="#aa7266b0c254907d979e9b31192e3e83f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2">FloatABI::ABIType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44277c39cd6496cc63dace4b1eb36bb7">FloatABIType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2ae41bda228a5aa7298dc5ac9cff9414f2">FloatABI::Default</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FloatABIType - This setting is set by -float-abi=xxx option is specfied on the command line. <a href="#a44277c39cd6496cc63dace4b1eb36bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5">FPOpFusion::FPOpFusionMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affeb69a55c900f2d333c385955676931">AllowFPOpFusion</a> = <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aff3d2f74200c0252e2912c6b605d94e9">FPOpFusion::Standard</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AllowFPOpFusion - This flag is set by the -fp-contract=xxx option. <a href="#affeb69a55c900f2d333c385955676931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/threadmodel/#a299c775d35e28348ecfbe03c38c17fe1">ThreadModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad71fd8f23965462454320f80024640c0">ThreadModel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/threadmodel/#a299c775d35e28348ecfbe03c38c17fe1abe9e16d2303bdffaf98672b16ab0e249">ThreadModel::POSIX</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/threadmodel">ThreadModel</a> - This flag specifies the type of threading model to assume for things like atomics. <a href="#ad71fd8f23965462454320f80024640c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91">EABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b8c72fed7a8b674600bf88d9042159a">EABIVersion</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91a7a1920d61156abc05a60135aefe8bc67">EABI::Default</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EABIVersion - This flag specifies the <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91">EABI</a> version. <a href="#a6b8c72fed7a8b674600bf88d9042159a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6">DebuggerKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3dcc2975d05bf20832ad55503483d0">DebuggerTuning</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a7a1920d61156abc05a60135aefe8bc67">DebuggerKind::Default</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which debugger to tune for. <a href="#a7d3dcc2975d05bf20832ad55503483d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84">ExceptionHandling</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af929c73622bbdd55d4190551fa813a9b">ExceptionModel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a6adf97f83acf6453d4a6a4b1070f3754">ExceptionHandling::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What exception model to use. <a href="#af929c73622bbdd55d4190551fa813a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cdbd949eef9cd8a1d5267d627cd9fb1">MCOptions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine level options. <a href="#a3cdbd949eef9cd8a1d5267d627cd9fb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f80b8e3905fe98a30a2aba9b1ea3dd8">ObjectFilenameForDebug</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the filename/path of the final .o/.obj file, to be written in the debug information. <a href="#a5f80b8e3905fe98a30a2aba9b1ea3dd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1bfb27619247cb02b93c815b778172">FPDenormalMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushing mode to assume in default FP environment. <a href="#a8d1bfb27619247cb02b93c815b778172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e8c0fb192733071a776a6ae4881c51">FP32DenormalMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushing mode to assume in default FP environment, for float/vector of float. <a href="#a98e8c0fb192733071a776a6ae4881c51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetOptions() {#af0f3705b7e516b390c0e162bac07f31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetOptions::TargetOptions ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>References <a href="#a6b45f941f3a7290a1c5f0e967df6c1c7">ApproxFuncFPMath</a>, <a href="#a4602186a8472e7bff53bd7a433b521e4">BBAddrMap</a>, <a href="#ad0c7f9f16d88de8a481dd162ead65c7f">DataSections</a>, <a href="#a8a0a6aa4b80c1d0652cce38e309bb97f">DebugStrictDwarf</a>, <a href="#af36a4179451e89551b53d4649e16d37f">DisableIntegratedAS</a>, <a href="#a266f996cc26e6ff405f3d5b7bfe16516">EmitAddrsig</a>, <a href="#a5eac77cb2f258f547232546b42dfe5c1">EmitCallSiteInfo</a>, <a href="#a0d4c8ac550351fbf544464a6a36f681e">EmitStackSizeSection</a>, <a href="#ae5ba34490ccea87c934d079ca6a8d09b">EmulatedTLS</a>, <a href="#a28e1d3fd3addb834a0bd9fd8b51f56e6">EnableAIXExtendedAltivecABI</a>, <a href="#a81d282653d72393cc4bb89953aa7a3d0">EnableCFIFixup</a>, <a href="#aea5b190e844a4fe4712507277bee42ad">EnableDebugEntryValues</a>, <a href="#ab26d50483184808463759bea1da917f8">EnableFastISel</a>, <a href="#acfac3721300d6e685b7543011b790e4a">EnableGlobalISel</a>, <a href="#acd366f946d1f11eeab165b83d98e2847">EnableIPRA</a>, <a href="#ac4e7bad531953b4136544c1a93d92d75">EnableMachineFunctionSplitter</a>, <a href="#a60d006266025255e4b084b3934ed1165">EnableMachineOutliner</a>, <a href="#a0d23dea0bb982335578481e1f4c7fe42">EnableTLSDESC</a>, <a href="#a4c8eedc7a0f349964f049852ff2f7db4">ForceDwarfFrameSection</a>, <a href="#abb646e2505e21a891497f665187963b3">FunctionSections</a>, <a href="#ad54fc81a4ef7ab96137a9b6e78fdf838">GuaranteedTailCallOpt</a>, <a href="#a75e4acf99d3d8efecb348006b189613f">HonorSignDependentRoundingFPMathOption</a>, <a href="#a718e851e53ea751a7f743509f02eedb9">Hotpatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a472abfae8142fdb6f39d081303e8af85">llvm::IEEE</a>, <a href="#a7df4dc95d9e4efbb514152b5f019cd36">IgnoreXCOFFVisibility</a>, <a href="#afd2600e9c715bbb82d1507e8f126afca">JMCInstrument</a>, <a href="#a60b873d6a142a16395fc64518f2f88db">MisExpect</a>, <a href="#a4d277b3eb8ea035973291fe90d27d280">NoInfsFPMath</a>, <a href="#aaf9cc05758a26e784f7cfa554e76f175">NoNaNsFPMath</a>, <a href="#a7fb34694aa403cda58ed7eff51e0ab2d">NoSignedZerosFPMath</a>, <a href="#acd83fce25de1ac9f6c975135a8235c22">NoTrapAfterNoreturn</a>, <a href="#af272560bf58c962e2c9e0af3e7a7c420">NoTrappingFPMath</a>, <a href="#a52f160f0506a9d8da975aac224fbcdbd">NoZerosInBSS</a>, <a href="#a92eafcc9e887aec1827bcb535825ecd4">PPCGenScalarMASSEntries</a>, <a href="#a661f99862caa07e96eaab915c23e610e">SeparateNamedSections</a>, <a href="#a3365678cbab08add568b0a7edb28fb09">StackSymbolOrdering</a>, <a href="#a6a26ddab8f249e51435d733e5aa44c1c">SupportsDebugEntryValues</a>, <a href="#a8a0dcb30ec6167a560d0a7fae85d608c">SupportsDefaultOutlining</a>, <a href="#aaab5140a64e553a0cbe994b783d6d0e6">TLSSize</a>, <a href="#ae511cb5018c52294bcff10ccde3f6789">TrapUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="#a93470bdcaa5df890c2b75fe7e9fc165b">UniqueBasicBlockSectionNames</a>, <a href="#aaeee4d390f75162b6cf22adb0f1fbb78">UniqueSectionNames</a>, <a href="#a0544e2966374684ff74255e5a4290fa7">UnsafeFPMath</a>, <a href="#a2b75286580e4346dbc5e186baa7e6b54">UseInitArray</a>, <a href="#a7654bf48dbcccca78653e82cee1c4d60">ValueTrackingVariableLocations</a>, <a href="#a0931af4649b2d1dcd3771f49971740f2">VerifyArgABICompliance</a>, <a href="#a116889d779045bd9d83925e41c86680b">XCOFFReadOnlyPointers</a>, <a href="#a7a43005dca46ff41b1da878c487f3edb">XCOFFTracebackTable</a> and <a href="#aeeaffd454df0057dd4a07fddfdab15ed">XRayFunctionIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DisableFramePointerElim() {#aad0fc1de8197ddf2c49346c5d92a2bec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetOptions::DisableFramePointerElim (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DisableFramePointerElim - This returns true if frame pointer elimination optimization should be disabled for the given machine function.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetoptionsimpl-cpp">TargetOptionsImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#aff8b6cd5f8dba25944e8d80ef4eb246b">llvm::ARMFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#adf86b81af5da74aea6a11c36eadf41be">llvm::AArch64RegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aa0eb9ad617a055468d105965502662c5">llvm::ARMBaseRegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a3ca8ff16a3bd8d5f7c682180151eb3fc">llvm::ARCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a895b02ce6ba256348e2eef839e1ef780">llvm::ARMFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a57e521638750a8eafb3e5b985cad6cb2">llvm::CSKYFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#adae83dd896dd68667b344defbc9c5381">llvm::LoongArchFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a0467fb31b542da4b9672b69ae002cf97">llvm::M68kFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#acc03bc4b3fe668894a31738a4f03269b">llvm::MipsFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a1b2778e918ea09d5b0f6e0d4ec0f3bc5">llvm::MSP430FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a6257e7a03156ea3018b555f0aff4b2">llvm::RISCVFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#abc1f60525acaf9f05557ea0d4bc1d339">llvm::SparcFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a639478d440d115bb94fd83bf9054da98">llvm::SystemZELFFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">llvm::VEFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ada8a1c1bcf75dee1d45143d3b8500d16">llvm::XCoreFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a130ce842392b2b6a8051ccfdf70b3d5a">llvm::XtensaFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a1aabb0d5da92e7ec4f977806b0f8d0ca">llvm::RISCVMachineFunctionInfo::isPushable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a26b78c90211732e17d6b4d5adede3d62">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### FramePointerIsReserved() {#aa56ae8efa388a7840c07b61e6a03b33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetOptions::FramePointerIsReserved (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FramePointerIsReserved - This returns true if the frame pointer must always either point to a new frame record or be un-modified in the given function.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetoptionsimpl-cpp">TargetOptionsImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a> and <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a5725394c4ad3c08a6a173b02827a32a3">llvm::ARMFrameLowering::isFPReserved</a>.</p>

</div>
</div>

### getDenormalMode() {#a0373cdd39b42d123ca7abb351aed1be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::TargetOptions::getDenormalMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; FPType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### getRawFP32DenormalMode() {#a6e1a122d0e6a6e7f72ef1d133d5c9b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::TargetOptions::getRawFP32DenormalMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### getRawFPDenormalMode() {#a2c31455d7fd7493c58a465fbde97bfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::TargetOptions::getRawFPDenormalMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### HonorSignDependentRoundingFPMath() {#a32054a115837c426986d56d382030345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetOptions::HonorSignDependentRoundingFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HonorSignDependentRoundingFPMath - Return true if the codegen must assume that the rounding mode of the FPU can change from its default.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetoptionsimpl-cpp">TargetOptionsImpl.cpp</a>.</p>


<p>References <a href="#a75e4acf99d3d8efecb348006b189613f">HonorSignDependentRoundingFPMathOption</a> and <a href="#a0544e2966374684ff74255e5a4290fa7">UnsafeFPMath</a>.</p>

</div>
</div>

### setFP32DenormalMode() {#a01decced737c074204373053cbf3febb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetOptions::setFP32DenormalMode (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> Mode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>

</div>
</div>

### setFPDenormalMode() {#a479c8c348a2ac67bcaf04394a8bf9bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetOptions::setFPDenormalMode (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> Mode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>

</div>
</div>

### ShouldEmitDebugEntryValues() {#af46038c2811d0b87e138a24317748729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetOptions::ShouldEmitDebugEntryValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NOTE: There are targets that still do not support the debug entry values production.</p>


<p>NOTE: There are targets that still do not support the debug entry values production and that is being controlled with the SupportsDebugEntryValues.</p>


<p>In addition, SCE debugger does not have the feature implemented, so prefer not to emit the debug entry values in that case. The EnableDebugEntryValues can be used for the testing purposes.</p>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetoptionsimpl-cpp">TargetOptionsImpl.cpp</a>.</p>


<p>References <a href="#a7d3dcc2975d05bf20832ad55503483d0">DebuggerTuning</a>, <a href="#aea5b190e844a4fe4712507277bee42ad">EnableDebugEntryValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a4f1fcf80c07532facc35db354783b0b2">llvm::SCE</a> and <a href="#a6a26ddab8f249e51435d733e5aa44c1c">SupportsDebugEntryValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllowFPOpFusion {#affeb69a55c900f2d333c385955676931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPOpFusion::FPOpFusionMode llvm::TargetOptions::AllowFPOpFusion = <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aff3d2f74200c0252e2912c6b605d94e9">FPOpFusion::Standard</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AllowFPOpFusion - This flag is set by the -fp-contract=xxx option.</p>


<p>This controls the creation of fused FP ops that store intermediate results in higher precision than IEEE allows (E.g. FMAs).</p>


<p>Fast mode - allows formation of fused FP ops whenever they're profitable. Standard mode - allow fusion only for 'blessed' FP ops. At present the only blessed op is the fmuladd intrinsic. In the future more blessed ops may be added. Strict mode - allow fusion only if/when it can be proven that the excess precision won't effect the result.</p>


<p>Note: This option only controls formation of fused ops by the optimizers. Fused operations that are explicitly specified (e.g. FMA via the llvm.fma.* intrinsic) will always be honored, regardless of the value of this option.</p>


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ada490959f8c0f210cd7843a1ebd04283">llvm::NVPTXTargetLowering::allowFMA</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>.</p>

</div>
</div>

### ApproxFuncFPMath {#a6b45f941f3a7290a1c5f0e967df6c1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::ApproxFuncFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ApproxFuncFPMath - This flag is enabled when the -enable-approx-func-fp-math is specified on the command line.</p>


<p>This specifies that optimizations are allowed to substitute math functions with approximate calculations</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### BBAddrMap {#a4602186a8472e7bff53bd7a433b521e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::BBAddrMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### BBSections {#a7375652c2b8022869f1a3b05440e0b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockSection llvm::TargetOptions::BBSections = <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a6adf97f83acf6453d4a6a4b1070f3754">BasicBlockSection::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit basic blocks into separate sections.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### BBSectionsFuncListBuf {#ab9d4c3547eb7f7c521500bda959e11c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;MemoryBuffer&gt; llvm::TargetOptions::BBSectionsFuncListBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Buffer that contains information on sampled basic blocks and used to selectively generate basic block sections.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### BinutilsVersion {#a46ba9a184ba490300fef429a79c1b7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt;int, int&gt; llvm::TargetOptions::BinutilsVersion {0, 0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If greater than 0, override the default value of <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae91d11081ad021098eed1c28e67992b6">MCAsmInfo::BinutilsVersion</a>.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### DataSections {#ad0c7f9f16d88de8a481dd162ead65c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::DataSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit data into separate sections.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>.</p>

</div>
</div>

### DebuggerTuning {#a7d3dcc2975d05bf20832ad55503483d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebuggerKind llvm::TargetOptions::DebuggerTuning = <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a7a1920d61156abc05a60135aefe8bc67">DebuggerKind::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which debugger to tune for.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="#af46038c2811d0b87e138a24317748729">ShouldEmitDebugEntryValues</a>.</p>

</div>
</div>

### DebugStrictDwarf {#a8a0a6aa4b80c1d0652cce38e309bb97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::DebugStrictDwarf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When set to true, don't use DWARF extensions in later DWARF versions.</p>


<p>By default, it is set to false.</p>


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### DisableIntegratedAS {#af36a4179451e89551b53d4649e16d37f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::DisableIntegratedAS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable the integrated assembler.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EABIVersion {#a6b8c72fed7a8b674600bf88d9042159a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EABI llvm::TargetOptions::EABIVersion = <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91a7a1920d61156abc05a60135aefe8bc67">EABI::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EABIVersion - This flag specifies the <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91">EABI</a> version.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### EmitAddrsig {#a266f996cc26e6ff405f3d5b7bfe16516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EmitAddrsig</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit address-significance table.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EmitCallSiteInfo {#a5eac77cb2f258f547232546b42dfe5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EmitCallSiteInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag enables call site info production.</p>


<p>It is used only for debug info, and it is restricted only to optimized code. This can be used for something else, so that should be controlled in the frontend.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EmitStackSizeSection {#a0d4c8ac550351fbf544464a6a36f681e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EmitStackSizeSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit section containing metadata on function stack sizes.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EmulatedTLS {#ae5ba34490ccea87c934d079ca6a8d09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EmulatedTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmulatedTLS - This flag enables emulated TLS model, using emutls function in the runtime library.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a0aa9eba1ffba47fd9e5ef90d81a30653">llvm::orc::irManglingOptionsFromTargetOptions</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableAIXExtendedAltivecABI {#a28e1d3fd3addb834a0bd9fd8b51f56e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableAIXExtendedAltivecABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EnableAIXExtendedAltivecABI - This flag returns true when -vec-extabi is specified.</p>


<p>The code generator is then able to use both volatile and nonvolitle vector registers. When false, the code generator only uses volatile vector registers which is the default setting on AIX.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableCFIFixup {#a81d282653d72393cc4bb89953aa7a3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableCFIFixup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable the <a href="/web-llvm/docs/api/classes/llvm/cfifixup">CFIFixup</a> pass.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableDebugEntryValues {#aea5b190e844a4fe4712507277bee42ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableDebugEntryValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When set to true, the EnableDebugEntryValues option forces production of debug entry values even if the target does not officially support it.</p>


<p>Useful for testing purposes only. This flag should never be checked directly, always use <a href="#af46038c2811d0b87e138a24317748729">ShouldEmitDebugEntryValues</a> instead.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af46038c2811d0b87e138a24317748729">ShouldEmitDebugEntryValues</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableFastISel {#ab26d50483184808463759bea1da917f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableFastISel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EnableFastISel - This flag enables fast-path instruction selection which trades away generated code quality in favor of reducing compile time.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a40e9166415077d71f840a81b21a1313a">llvm::MipsTargetLowering::createFastISel</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableGlobalISel {#acfac3721300d6e685b7543011b790e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableGlobalISel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EnableGlobalISel - This flag enables global instruction selection.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableIPRA {#acd366f946d1f11eeab165b83d98e2847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableIPRA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This flag enables InterProcedural <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Allocation (IPRA).</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableMachineFunctionSplitter {#ac4e7bad531953b4136544c1a93d92d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableMachineFunctionSplitter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enables the MachineFunctionSplitter pass.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableMachineOutliner {#a60d006266025255e4b084b3934ed1165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableMachineOutliner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enables the MachineOutliner pass.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### EnableTLSDESC {#a0d23dea0bb982335578481e1f4c7fe42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::EnableTLSDESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EnableTLSDESC - This flag enables TLS Descriptors.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### ExceptionModel {#af929c73622bbdd55d4190551fa813a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExceptionHandling llvm::TargetOptions::ExceptionModel = <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a6adf97f83acf6453d4a6a4b1070f3754">ExceptionHandling::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>What exception model to use.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### FloatABIType {#a44277c39cd6496cc63dace4b1eb36bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FloatABI::ABIType llvm::TargetOptions::FloatABIType = <a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2ae41bda228a5aa7298dc5ac9cff9414f2">FloatABI::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FloatABIType - This setting is set by -float-abi=xxx option is specfied on the command line.</p>


<p>This setting may either be Default, Soft, or Hard. Default selects the target's default behavior. Soft selects the ABI for software floating point, but does not indicate that FP hardware may not be used. Such a combination is unfortunately popular (e.g. arm-apple-darwin). Hard presumes that the normal FP ABI is used.</p>


<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskysubtarget/#a96135156edd232b1c1a1e5237e033c1d">llvm::CSKYSubtarget::useHardFloatABI</a>.</p>

</div>
</div>

### ForceDwarfFrameSection {#a4c8eedc7a0f349964f049852ff2f7db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::ForceDwarfFrameSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit DWARF debug frame section.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### FunctionSections {#abb646e2505e21a891497f665187963b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::FunctionSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit functions into separate sections.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>.</p>

</div>
</div>

### GlobalISelAbort {#a790b23e61a3ec34a2910114f261e6dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalISelAbortMode llvm::TargetOptions::GlobalISelAbort = <a href="/web-llvm/docs/api/namespaces/llvm/#af69c47ced839e86a65b94b0a33ee5c2aa2faec1f9f8cc7f8f40d521c4dd574f49">GlobalISelAbortMode::Enable</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EnableGlobalISelAbort - Control abort behaviour when global instruction selection fails to lower/select an instruction.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### GuaranteedTailCallOpt {#ad54fc81a4ef7ab96137a9b6e78fdf838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::GuaranteedTailCallOpt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GuaranteedTailCallOpt - This flag is enabled when -tailcallopt is specified on the commandline.</p>


<p>When the flag is on, participating targets will perform tail call optimization on all calls which use the fastcc calling convention and which satisfy certain target-independent criteria (being at the end of a function, having the same return type as their parent function, etc.), using an alternate ABI if necessary.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a63c498f1fcb62301a44ad58e2dc8e7fc">llvm::PPCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a1c1ba0852c28df8598b5a0d2f0abb3aa">llvm::AMDGPUCallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### HonorSignDependentRoundingFPMathOption {#a75e4acf99d3d8efecb348006b189613f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::HonorSignDependentRoundingFPMathOption</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HonorSignDependentRoundingFPMath - This returns true when the -enable-sign-dependent-rounding-fp-math is specified.</p>


<p>If this returns false (the default), the code generator is allowed to assume that the rounding behavior is the default (round-to-zero for all floating point to integer conversions, and round-to-nearest for all other arithmetic truncations). If this is enabled (set to true), the code generator must assume that the rounding mode may dynamically change.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#a32054a115837c426986d56d382030345">HonorSignDependentRoundingFPMath</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### Hotpatch {#a718e851e53ea751a7f743509f02eedb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::Hotpatch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the hotpatch flag in CodeView debug.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### IgnoreXCOFFVisibility {#a7df4dc95d9e4efbb514152b5f019cd36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::IgnoreXCOFFVisibility</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do not emit visibility attribute for xcoff.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### JMCInstrument {#afd2600e9c715bbb82d1507e8f126afca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::JMCInstrument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable JustMyCode instrumentation.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### LoopAlignment {#aa7266b0c254907d979e9b31192e3e83f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::LoopAlignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If greater than 0, override TargetLoweringBase::PrefLoopAlignment.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### MCOptions {#a3cdbd949eef9cd8a1d5267d627cd9fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetOptions llvm::TargetOptions::MCOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine level options.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/groups/llvmctarget/#gad5c3bf4cc627842e1987abae68f676de">LLVMCreateTargetMachineWithOptions</a>.</p>

</div>
</div>

### MisExpect {#a60b873d6a142a16395fc64518f2f88db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::MisExpect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When set to true, enable MisExpect Diagnostics By default, it is set to false.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### NoInfsFPMath {#a4d277b3eb8ea035973291fe90d27d280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoInfsFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NoInfsFPMath - This flag is enabled when the -enable-no-infs-fp-math flag is specified on the command line.</p>


<p>When this flag is off (the default), the code generator is not allowed to assume the FP arithmetic arguments and results are never +-Infs.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### NoNaNsFPMath {#aaf9cc05758a26e784f7cfa554e76f175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoNaNsFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NoNaNsFPMath - This flag is enabled when the -enable-no-nans-fp-math flag is specified on the command line.</p>


<p>When this flag is off (the default), the code generator is not allowed to assume the FP arithmetic arguments and results are never NaNs.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81efb38c390b38633dbdb3e877a15a84">combineFMinFMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### NoSignedZerosFPMath {#a7fb34694aa403cda58ed7eff51e0ab2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoSignedZerosFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NoSignedZerosFPMath - This flag is enabled when the -enable-no-signed-zeros-fp-math is specified on the command line.</p>


<p>This specifies that optimizations are allowed to treat the sign of a zero argument or result as insignificant.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81efb38c390b38633dbdb3e877a15a84">combineFMinFMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a904fa902f773c900d99c77af2da331c1">foldFPToIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### NoTrapAfterNoreturn {#acd83fce25de1ac9f6c975135a8235c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoTrapAfterNoreturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do not emit a trap instruction for 'unreachable' IR instructions behind noreturn calls, even if TrapUnreachable is true.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afff13ac7b2e92fc0ad596603592298bd">llvm::SelectionDAGBuilder::visitSPDescriptorFailure</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>.</p>

</div>
</div>

### NoTrappingFPMath {#af272560bf58c962e2c9e0af3e7a7c420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoTrappingFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NoTrappingFPMath - This flag is enabled when the -enable-no-trapping-fp-math is specified on the command line.</p>


<p>This specifies that there are no trap handlers to handle exceptions.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### NoZerosInBSS {#a52f160f0506a9d8da975aac224fbcdbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::NoZerosInBSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NoZerosInBSS - By default some codegens place zero-initialized data to .bss section.</p>


<p>This flag disables such behaviour (necessary, e.g. for crt*.o compiling).</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### ObjectFilenameForDebug {#a5f80b8e3905fe98a30a2aba9b1ea3dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TargetOptions::ObjectFilenameForDebug</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the filename/path of the final .o/.obj file, to be written in the debug information.</p>


<p>This is used for emitting the CodeView S_OBJNAME record.</p>


<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### PPCGenScalarMASSEntries {#a92eafcc9e887aec1827bcb535825ecd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::PPCGenScalarMASSEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enables scalar MASS conversions.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### SeparateNamedSections {#a661f99862caa07e96eaab915c23e610e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::SeparateNamedSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit named sections with the same name into different sections.</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### StackSymbolOrdering {#a3365678cbab08add568b0a7edb28fb09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::StackSymbolOrdering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StackSymbolOrdering - When true, this will allow CodeGen to order the local stack symbols (for code size, code locality, or any other heuristics).</p>


<p>When false, the local symbols are left in whatever order they were generated. Default is true.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### StackUsageOutput {#acc1769477c512bc934a7066b9024fb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TargetOptions::StackUsageOutput</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name of the stack usage file (i.e., .su file) if user passes -fstack-usage.</p>


<p>If empty, it can be implied that -fstack-usage is not passed on the command line.</p>


<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### SupportsDebugEntryValues {#a6a26ddab8f249e51435d733e5aa44c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::SupportsDebugEntryValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set if the target supports the debug entry values by default.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af46038c2811d0b87e138a24317748729">ShouldEmitDebugEntryValues</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### SupportsDefaultOutlining {#a8a0dcb30ec6167a560d0a7fae85d608c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::SupportsDefaultOutlining</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set if the target supports default outlining behaviour.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### SwiftAsyncFramePointer {#a66a62a15c006f8bc55698e0bea465699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwiftAsyncFramePointerMode llvm::TargetOptions::SwiftAsyncFramePointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Control when and how the Swift async frame pointer bit should be set.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
        <a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34a68eec46437c384d8dad18d5464ebc35c">SwiftAsyncFramePointerMode::Always</a>
</div>
</dd>
</dl>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### ThreadModel {#ad71fd8f23965462454320f80024640c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadModel::Model llvm::TargetOptions::ThreadModel = <a href="/web-llvm/docs/api/namespaces/llvm/threadmodel/#a299c775d35e28348ecfbe03c38c17fe1abe9e16d2303bdffaf98672b16ab0e249">ThreadModel::POSIX</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/threadmodel">ThreadModel</a> - This flag specifies the type of threading model to assume for things like atomics.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### TLSSize {#aaab5140a64e553a0cbe994b783d6d0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::TLSSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bit size of immediate TLS offsets (0 == use the default).</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### TrapUnreachable {#ae511cb5018c52294bcff10ccde3f6789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::TrapUnreachable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target-specific trap instruction for 'unreachable' IR instructions.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afff13ac7b2e92fc0ad596603592298bd">llvm::SelectionDAGBuilder::visitSPDescriptorFailure</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>.</p>

</div>
</div>

### UniqueBasicBlockSectionNames {#a93470bdcaa5df890c2b75fe7e9fc165b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::UniqueBasicBlockSectionNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> unique names for basic block sections.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### UniqueSectionNames {#aaeee4d390f75162b6cf22adb0f1fbb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::UniqueSectionNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a39f4b4edb8abb1954310e3b6915afc81">llvm::WebAssemblyTargetMachine::WebAssemblyTargetMachine</a>.</p>

</div>
</div>

### UnsafeFPMath {#a0544e2966374684ff74255e5a4290fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::UnsafeFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UnsafeFPMath - This flag is enabled when the -enable-unsafe-fp-math flag is specified on the command line.</p>


<p>When this flag is off (the default), the code generator is not allowed to produce results that are "less precise" than IEEE allows. This includes use of <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> instructions like FSIN and FCOS instead of libcalls.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#aed1455dbc1ee69a6b745c72fdecac52f">llvm::NVPTXTargetLowering::allowUnsafeFPMath</a>, <a href="#a32054a115837c426986d56d382030345">HonorSignDependentRoundingFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab3d65d6e0daa1da2c564a3803f207b2">llvm::AArch64InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aa71647a93d5e73c28332b6e52407979c">llvm::AMDGPULegalizerInfo::legalizeFastUnsafeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac0184339c875630ffed0e19b55899b82">llvm::AMDGPULegalizerInfo::legalizeFastUnsafeFDIV64</a>, <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ae520d99d1f2920afdc21bdd7346ba561">llvm::NVPTXTargetLowering::usePrecSqrtF32</a>.</p>

</div>
</div>

### UseInitArray {#a2b75286580e4346dbc5e186baa7e6b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::UseInitArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UseInitArray - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> .init_array instead of .ctors for static constructors.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a> and <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### ValueTrackingVariableLocations {#a7654bf48dbcccca78653e82cee1c4d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::ValueTrackingVariableLocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### VerifyArgABICompliance {#a0931af4649b2d1dcd3771f49971740f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::VerifyArgABICompliance</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When set to true, call/return argument extensions of narrow integers are verified in the target backend if it cares about them.</p>


<p>This is not done with internal tools like llc that run many tests that ignore (lack) these extensions.</p>


<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### XCOFFReadOnlyPointers {#a116889d779045bd9d83925e41c86680b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::XCOFFReadOnlyPointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When set to true, const objects with relocatable address values are put into the RO data section.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### XCOFFTracebackTable {#a7a43005dca46ff41b1da878c487f3edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::XCOFFTracebackTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> traceback table.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

### XRayFunctionIndex {#aeeaffd454df0057dd4a07fddfdab15ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetOptions::XRayFunctionIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit XRay <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Index section.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>


<p>Referenced by <a href="#af0f3705b7e516b390c0e162bac07f31c">TargetOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FP32DenormalMode {#a98e8c0fb192733071a776a6ae4881c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::TargetOptions::FP32DenormalMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flushing mode to assume in default FP environment, for float/vector of float.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

### FPDenormalMode {#a8d1bfb27619247cb02b93c815b778172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::TargetOptions::FPDenormalMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flushing mode to assume in default FP environment.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">TargetOptions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetoptionsimpl-cpp">TargetOptionsImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

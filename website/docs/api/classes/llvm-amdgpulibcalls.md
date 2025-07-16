---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpulibcalls
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPULibCalls` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPULibCalls { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e734d0fe4de57cda357c7deb102d538">FuncInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">llvm::AMDGPULibFunc</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae270226dc1d6b924308716c8b482b76d">AMDGPULibCalls</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615317b48f533b3087abb06d3a96319c">fold</a> (CallInst *CI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3e6b1b364abb13d8c1b1a79a971481">initFunction</a> (Function &amp;F, FunctionAnalysisManager &amp;FAM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b1fc9079cbd516aa873d15359a0c0b">initNativeFuncs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab013e5e37e15eee5725a24b6a6df2416">useNative</a> (CallInst *CI)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57024f93dc2316eb9cc3751f0ae766e">isUnsafeMath</a> (const FPMathOperator *FPOp) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1b147c616566686d22c1a730f747f9">isUnsafeFiniteOnlyMath</a> (const FPMathOperator *FPOp) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbf80f261f74ef532d64af8314892f5">canIncreasePrecisionOfConstantFold</a> (const FPMathOperator *FPOp) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad92525b998620a9fe509d6673611930">useNativeFunc</a> (const StringRef F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c478cdd363635bd1d4f3ae24f75349">getFunction</a> (Module *M, const FuncInfo &amp;fInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3afff819e77d5afaed694c62db18554">parseFunctionName</a> (const StringRef &amp;FMangledName, FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718825773983dc935e1d18b7e9243522">TDOFold</a> (CallInst *CI, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa6fa016ab1cf49fc0b2483d58dc384">fold_pow</a> (FPMathOperator *FPOp, IRBuilder&lt;&gt; &amp;B, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101c0bb9b8b01740800c16baa00c730b">fold_rootn</a> (FPMathOperator *FPOp, IRBuilder&lt;&gt; &amp;B, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49d14df38c9ad994ea4cdb4ae6075b8">sincosUseNative</a> (CallInst *aCI, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6328d73f8bc0c6bf1fe54edcd55aaeec">evaluateScalarMathFunc</a> (const FuncInfo &amp;FInfo, double &amp;Res0, double &amp;Res1, Constant *copr0, Constant *copr1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527dfdb342f97143c583b7ec5c483da1">evaluateCall</a> (CallInst *aCI, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b554fd32b53f39540254a389bffc4c">insertSinCos</a> (Value *Arg, FastMathFlags FMF, IRBuilder&lt;&gt; &amp;B, FunctionCallee Fsincos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a value to sincos function <span class="doxyComputerOutput">Fsincos</span>. <a href="#a64b554fd32b53f39540254a389bffc4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c01febce1489c459a5fcbfc0074f852">fold_sincos</a> (FPMathOperator *FPOp, IRBuilder&lt;&gt; &amp;B, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad678417f2bdba2d21b4231cf637b521c">fold_read_write_pipe</a> (CallInst *CI, IRBuilder&lt;&gt; &amp;B, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4574c5bddb131ace925aa61b4c9c548">getNativeFunction</a> (Module *M, const FuncInfo &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184bc463ed5fa0cfab9ee68630f29c8c">shouldReplaceLibcallWithIntrinsic</a> (const CallInst *CI, bool AllowMinSizeF32=false, bool AllowF64=false, bool AllowStrictFP=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Substitute a call to a known libcall with an intrinsic call. <a href="#a184bc463ed5fa0cfab9ee68630f29c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55cd41a6da20ff6dfdab025f72c892cd">replaceLibCallWithSimpleIntrinsic</a> (IRBuilder&lt;&gt; &amp;B, CallInst *CI, Intrinsic::ID IntrID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291b00a267097294ae0f5f8c9a589897">tryReplaceLibcallWithSimpleIntrinsic</a> (IRBuilder&lt;&gt; &amp;B, CallInst *CI, Intrinsic::ID IntrID, bool AllowMinSizeF32=false, bool AllowF64=false, bool AllowStrictFP=false)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151ae73c9b16ab33ee0132c8014cb5e6">TLInfo</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae151b95b924a2268a4220a0af1ce39ab">AC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4fcfe0632dbd29b3b83fa8383c6fc9">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab789e9bc28c620e182e21fb923bbf587">UnsafeFPMath</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e3b5d43360e5b4d4196468e1c296dc">AllNative</a> = false</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750c956ba306a9f467e78f75d62a3085">replaceCall</a> (Instruction *I, Value *With)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a59ad5627d3eaf2d0d397dc68361bc5">replaceCall</a> (FPMathOperator *I, Value *With)</td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FuncInfo {#a0e734d0fe4de57cda357c7deb102d538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPULibCalls::FuncInfo =  llvm::AMDGPULibFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPULibCalls() {#ae270226dc1d6b924308716c8b482b76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPULibCalls::AMDGPULibCalls ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fold() {#a615317b48f533b3087abb06d3a96319c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::fold (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a3dbf80f261f74ef532d64af8314892f5">canIncreasePrecisionOfConstantFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad164187e4f9f1fc16a86d166b9793ac3">llvm::cannotBeOrderedLessThanZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a0cd4c1b138d87489a1a582464de79251">llvm::AMDGPULibFuncBase::EI_CEIL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3acf381ecf66f7217601c09feea36d6ed0">llvm::AMDGPULibFuncBase::EI_COPYSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3adb71933f23940e062fc5a3eac31ccc11">llvm::AMDGPULibFuncBase::EI_COS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2e987433a67ea17eda081f27ecd098db">llvm::AMDGPULibFuncBase::EI_EXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a49bd67da9ac6801dcfaa8ef97e2960d3">llvm::AMDGPULibFuncBase::EI_EXP2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3aa96a2dd6e72dc1ca41d42d6c44846723">llvm::AMDGPULibFuncBase::EI_FABS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a058384d09ec72e7b4581eabcf6934000">llvm::AMDGPULibFuncBase::EI_FLOOR</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a48fbb1e41e5234f2cb1635c540aed4c6">llvm::AMDGPULibFuncBase::EI_FMA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a94a21632abaf14faf328a76f55125914">llvm::AMDGPULibFuncBase::EI_FMAX</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a8491579b710e291a7d09e6a9f7c70ca0">llvm::AMDGPULibFuncBase::EI_FMIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a0eafdc097e558d07f2185458cea061c1">llvm::AMDGPULibFuncBase::EI_LDEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab5e69549fb42b96e18a69c438e1f9761">llvm::AMDGPULibFuncBase::EI_LOG</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a52a423fd81e8bb4925add23cb778498c">llvm::AMDGPULibFuncBase::EI_LOG10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3afe8ecaad2f1178bc0a4f3e3ca266ec6d">llvm::AMDGPULibFuncBase::EI_LOG2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a8483b653f23fe91a91f1dc14f41724d3">llvm::AMDGPULibFuncBase::EI_MAD</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3af5e703d690b2fc7009da2e7ea28b038e">llvm::AMDGPULibFuncBase::EI_POW</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a3d6c3f390e6c5e88b199ad76ab6927f4">llvm::AMDGPULibFuncBase::EI_POWN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a890b3d788fc247f94186955daaedaa12">llvm::AMDGPULibFuncBase::EI_POWR</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a857a85237617df4bef89cc3b681ed391">llvm::AMDGPULibFuncBase::EI_READ_PIPE_2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2dd4b1948ce322d57d3fd12bd7234abd">llvm::AMDGPULibFuncBase::EI_READ_PIPE_4</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3abbfa421d45576bfd76fdee8b028c1794">llvm::AMDGPULibFuncBase::EI_RINT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a9d833f07a7a25855cf524a3dd54556fe">llvm::AMDGPULibFuncBase::EI_ROOTN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a8416fd02482dc92eb84c2c38eee70db7">llvm::AMDGPULibFuncBase::EI_ROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a9de3a011a924c901cd12142bf48a83ec">llvm::AMDGPULibFuncBase::EI_SIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2d19318cd15f1d0bc987640a6545419a">llvm::AMDGPULibFuncBase::EI_SQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a6a6b5da17a2e439c886a2f085ae972e9">llvm::AMDGPULibFuncBase::EI_TRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3af981794446493eb20f572fc644af8a35">llvm::AMDGPULibFuncBase::EI_WRITE_PIPE_2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a16dcaa516691259b2ebf9aec3f010cda">llvm::AMDGPULibFuncBase::EI_WRITE_PIPE_4</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a952054860730d393bd849f67e3b56cbb">llvm::AMDGPULibFunc::getId</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#adfa93be20aafc0740ce9e4d48640406c">getPownType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a8e662f55e8be621fac1827a2032c217a">llvm::AMDGPULibFunc::isCompatibleSignature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1fb374eb65dcf7cd3d1671efb2616f76">llvm::CallBase::isNoBuiltin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a300433f583bb9e2862b84df663f43f40">llvm::CallBase::isStrictFP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a3c72e480015b1ffdcd0382fa46437806">llvm::FastMathFlags::none</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aee56a5257c4899bf97c5957d87a732e3">llvm::CallBase::setCalledFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpusimplifylibcallspass/#ae83c4c6a3cf049dbac4ce40c2fa476dd">llvm::AMDGPUSimplifyLibCallsPass::run</a>.</p>

</div>
</div>

### initFunction() {#ace3e6b1b364abb13d8c1b1a79a971481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPULibCalls::initFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpusimplifylibcallspass/#ae83c4c6a3cf049dbac4ce40c2fa476dd">llvm::AMDGPUSimplifyLibCallsPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>.</p>

</div>
</div>

### initNativeFuncs() {#a64b1fc9079cbd516aa873d15359a0c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPULibCalls::initNativeFuncs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#af1d374fe79be31cc3d1acd2a31a1ec01">UseNative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpusimplifylibcallspass/#ae83c4c6a3cf049dbac4ce40c2fa476dd">llvm::AMDGPUSimplifyLibCallsPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>.</p>

</div>
</div>

### useNative() {#ab013e5e37e15eee5725a24b6a6df2416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::useNative (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a19916d6858eb73c5cafdadb79ebde8ed">llvm::AMDGPULibFuncBase::EI_SINCOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562">llvm::AMDGPULibFuncBase::F64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a0b53d60342909a86b16824b265a29a4b">getArgType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a952054860730d393bd849f67e3b56cbb">llvm::AMDGPULibFunc::getId</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a3d2c4ace0f45db8a165b36ebc752afd3">llvm::AMDGPULibFunc::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#aedf45ade500680ec798eaa77d6a5947f">llvm::AMDGPULibFunc::getPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a5dbbc20ea13b965c7622e591e09113d8">HasNative</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#aa75f08ed6cd0bf0376105ae51ca8d205">llvm::AMDGPULibFunc::isMangled</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1fb374eb65dcf7cd3d1671efb2616f76">llvm::CallBase::isNoBuiltin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a1df3c3e4573abf56929068a57e3f4963">llvm::AMDGPULibFuncBase::NATIVE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a4e02cec40ee27126cc5262e46bd59e03">llvm::AMDGPULibFuncBase::NOPFX</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aee56a5257c4899bf97c5957d87a732e3">llvm::CallBase::setCalledFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a6f485057bcb2006defd79fb50ad13944">llvm::AMDGPULibFunc::setPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### canIncreasePrecisionOfConstantFold() {#a3dbf80f261f74ef532d64af8314892f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::canIncreasePrecisionOfConstantFold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Reference <a href="#af57024f93dc2316eb9cc3751f0ae766e">isUnsafeMath</a>.</p>


<p>Referenced by <a href="#a615317b48f533b3087abb06d3a96319c">fold</a>.</p>

</div>
</div>

### isUnsafeFiniteOnlyMath() {#a3a1b147c616566686d22c1a730f747f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::isUnsafeFiniteOnlyMath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af033630a6f4a852c95625648b3f893c6">llvm::FPMathOperator::hasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#ae6d93d933e7e2e0d11075507102317d7">llvm::FPMathOperator::hasNoInfs</a> and <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a81877288bdf18216272d7724ecb894c8">llvm::FPMathOperator::hasNoNaNs</a>.</p>

</div>
</div>

### isUnsafeMath() {#af57024f93dc2316eb9cc3751f0ae766e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::isUnsafeMath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a0f3e20e19cc93a7cf75fbe6b4b27a728">llvm::FPMathOperator::isFast</a>.</p>


<p>Referenced by <a href="#a3dbf80f261f74ef532d64af8314892f5">canIncreasePrecisionOfConstantFold</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateCall() {#a527dfdb342f97143c583b7ec5c483da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::evaluateCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * aCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### evaluateScalarMathFunc() {#a6328d73f8bc0c6bf1fe54edcd55aaeec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::evaluateScalarMathFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo, double &amp; Res0, double &amp; Res1, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * copr0, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * copr1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### fold\_pow() {#a9aa6fa016ab1cf49fc0b2483d58dc384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::fold_pow (<a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### fold\_read\_write\_pipe() {#ad678417f2bdba2d21b4231cf637b521c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::fold_read_write_pipe (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### fold\_rootn() {#a101c0bb9b8b01740800c16baa00c730b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::fold_rootn (<a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### fold\_sincos() {#a4c01febce1489c459a5fcbfc0074f852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::fold_sincos (<a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPOp, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### getFunction() {#a55c478cdd363635bd1d4f3ae24f75349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee AMDGPULibCalls::getFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; fInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### getNativeFunction() {#ab4574c5bddb131ace925aa61b4c9c548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee AMDGPULibCalls::getNativeFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### insertSinCos() {#a64b554fd32b53f39540254a389bffc4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Value *, Value *, Value * &gt; AMDGPULibCalls::insertSinCos (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Fsincos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a value to sincos function <span class="doxyComputerOutput">Fsincos</span>.</p>


<p>Returns (value of sin, value of cos, sincos call).</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### parseFunctionName() {#aa3afff819e77d5afaed694c62db18554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::parseFunctionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FMangledName, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### replaceLibCallWithSimpleIntrinsic() {#a55cd41a6da20ff6dfdab025f72c892cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPULibCalls::replaceLibCallWithSimpleIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### shouldReplaceLibcallWithIntrinsic() {#a184bc463ed5fa0cfab9ee68630f29c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::shouldReplaceLibcallWithIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, bool AllowMinSizeF32=false, bool AllowF64=false, bool AllowStrictFP=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Substitute a call to a known libcall with an intrinsic call.</p>


<p>If <span class="doxyComputerOutput">AllowMinSize</span> is true, allow the replacement in a minsize function.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### sincosUseNative() {#aa49d14df38c9ad994ea4cdb4ae6075b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::sincosUseNative (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * aCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### TDOFold() {#a718825773983dc935e1d18b7e9243522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::TDOFold (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">FuncInfo</a> &amp; FInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### tryReplaceLibcallWithSimpleIntrinsic() {#a291b00a267097294ae0f5f8c9a589897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::tryReplaceLibcallWithSimpleIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrID, bool AllowMinSizeF32=false, bool AllowF64=false, bool AllowStrictFP=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### useNativeFunc() {#aad92525b998620a9fe509d6673611930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULibCalls::useNativeFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#ae151b95b924a2268a4220a0af1ce39ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::AMDGPULibCalls::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### AllNative {#a11e3b5d43360e5b4d4196468e1c296dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPULibCalls::AllNative = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### DT {#a9d4fcfe0632dbd29b3b83fa8383c6fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::AMDGPULibCalls::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### TLInfo {#a151ae73c9b16ab33ee0132c8014cb5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::AMDGPULibCalls::TLInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### UnsafeFPMath {#ab789e9bc28c620e182e21fb923bbf587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPULibCalls::UnsafeFPMath = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### replaceCall() {#a750c956ba306a9f467e78f75d62a3085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibCalls::replaceCall (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * With)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a0a59ad5627d3eaf2d0d397dc68361bc5">replaceCall</a>.</p>

</div>
</div>

### replaceCall() {#a0a59ad5627d3eaf2d0d397dc68361bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibCalls::replaceCall (<a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * With)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a750c956ba306a9f467e78f75d62a3085">replaceCall</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

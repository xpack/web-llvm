---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpulibfuncimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPULibFuncImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPULibFuncImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">Target/AMDGPU/AMDGPULibFunc.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase">AMDGPULibFuncBase</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc">AMDGPUMangledLibFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc">AMDGPUUnmangledLibFunc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb31ccdc25fa76bbb01ef85b17d6845">AMDGPULibFuncImpl</a> ()=default</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abacda90a1842cf1338916f11c1f85fee">~AMDGPULibFuncImpl</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79b36ec1ac61405e9f24445cfb04cad">getName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get unmangled name for mangled library function and name for unmangled library function. <a href="#af79b36ec1ac61405e9f24445cfb04cad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcb1d3f42bc1c5494514952aaf31c8c">getNumArgs</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3">EFuncId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650c5241880c78cf43518887f52c464d">getId</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6">ENamePrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937749fe517c43d71555f68fbb8169b4">getPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa8c9c63acfecd412c590d7142a634f">isMangled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd154b90e347f7ef5fc8681543ebc86">setId</a> (EFuncId id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78753a58e3bc356825a26868eb6af068">parseFuncName</a> (StringRef &amp;mangledName)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc3dd5c741051952ef0ce95cb00f1ab">mangle</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad783e6edf33f340d74a7b8ecde825ee6">setName</a> (StringRef N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1cc41f79230a37b4149dd7ed8e531c1">setPrefix</a> (ENamePrefix pfx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d62ab2a7f36978fe43d7b1214805c8">getFunctionType</a> (const Module &amp;M) const =0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3">EFuncId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e13b97adb19f8e9655075004c5db66f">FuncId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97bf3cc52e6bbc6ff75ddd349faa795">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6">ENamePrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc712a3b668873b9b5ebb5d31483ddf">FKind</a> = <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a4e02cec40ee27126cc5262e46bd59e03">NOPFX</a></td>
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


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPULibFuncImpl() {#a5cb31ccdc25fa76bbb01ef85b17d6845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPULibFuncImpl::AMDGPULibFuncImpl ()</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a81427ec20a8ed1c8ad615d0a95657cbf">llvm::AMDGPUMangledLibFunc::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a01c4d30670d0ec2d9d31252d8f56797a">llvm::AMDGPUUnmangledLibFunc::classof</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPULibFuncImpl() {#abacda90a1842cf1338916f11c1f85fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AMDGPULibFuncImpl::~AMDGPULibFuncImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFunctionType() {#a50d62ab2a7f36978fe43d7b1214805c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FunctionType * llvm::AMDGPULibFuncImpl::getFunctionType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### getId() {#a650c5241880c78cf43518887f52c464d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EFuncId llvm::AMDGPULibFuncImpl::getId ()</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="#a1e13b97adb19f8e9655075004c5db66f">FuncId</a>.</p>

</div>
</div>

### getName() {#af79b36ec1ac61405e9f24445cfb04cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::AMDGPULibFuncImpl::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get unmangled name for mangled library function and name for unmangled library function.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### getNumArgs() {#a7fcb1d3f42bc1c5494514952aaf31c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::AMDGPULibFuncImpl::getNumArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### getPrefix() {#a937749fe517c43d71555f68fbb8169b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ENamePrefix llvm::AMDGPULibFuncImpl::getPrefix ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="#a5fc712a3b668873b9b5ebb5d31483ddf">FKind</a>.</p>

</div>
</div>

### isMangled() {#aeaa8c9c63acfecd412c590d7142a634f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPULibFuncImpl::isMangled ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>References <a href="#a1e13b97adb19f8e9655075004c5db66f">FuncId</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a656ff82f4700daf658142eef8eb184d2">llvm::AMDGPULibFuncBase::isMangled</a>.</p>

</div>
</div>

### mangle() {#a2fc3dd5c741051952ef0ce95cb00f1ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::AMDGPULibFuncImpl::mangle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The mangled function name for mangled library functions and unmangled function name for unmangled library functions.</p></dd>
</dl>


<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### parseFuncName() {#a78753a58e3bc356825a26868eb6af068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AMDGPULibFuncImpl::parseFuncName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; mangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### setId() {#afdd154b90e347f7ef5fc8681543ebc86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibFuncImpl::setId (<a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3">EFuncId</a> id)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="#a1e13b97adb19f8e9655075004c5db66f">FuncId</a>.</p>

</div>
</div>

### setName() {#ad783e6edf33f340d74a7b8ecde825ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibFuncImpl::setName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> N)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af97bf3cc52e6bbc6ff75ddd349faa795">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a7c0ca54e69238594591bb95cefe84844">llvm::AMDGPUUnmangledLibFunc::parseFuncName</a>.</p>

</div>
</div>

### setPrefix() {#ac1cc41f79230a37b4149dd7ed8e531c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibFuncImpl::setPrefix (<a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6">ENamePrefix</a> pfx)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="#a5fc712a3b668873b9b5ebb5d31483ddf">FKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FKind {#a5fc712a3b668873b9b5ebb5d31483ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ENamePrefix llvm::AMDGPULibFuncImpl::FKind = <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a4e02cec40ee27126cc5262e46bd59e03">NOPFX</a></td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#ae6bb0cb8a9e02a75f49701e0a16dc2a2">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a4c17450f81d6cf97d3ad531a3b610199">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="#a937749fe517c43d71555f68fbb8169b4">getPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a753bb73906fd815420f857b61252aaad">llvm::AMDGPUMangledLibFunc::parseFuncName</a> and <a href="#ac1cc41f79230a37b4149dd7ed8e531c1">setPrefix</a>.</p>

</div>
</div>

### FuncId {#a1e13b97adb19f8e9655075004c5db66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EFuncId llvm::AMDGPULibFuncImpl::FuncId</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#ae6bb0cb8a9e02a75f49701e0a16dc2a2">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a4c17450f81d6cf97d3ad531a3b610199">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a584bad5329b738a08334d55310c2a94b">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a689f62d8ae07d330d6607dd5965293de">llvm::AMDGPUUnmangledLibFunc::AMDGPUUnmangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#aa6728197a535e01349675bcc721e56c3">llvm::AMDGPUMangledLibFunc::getFunctionType</a>, <a href="#a650c5241880c78cf43518887f52c464d">getId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a6f5940339246d1aeef46ac1b61fad188">llvm::AMDGPUMangledLibFunc::getNumArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a0e40d0f5b8e766efcbccd45c611c7f2f">llvm::AMDGPUUnmangledLibFunc::getNumArgs</a>, <a href="#aeaa8c9c63acfecd412c590d7142a634f">isMangled</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a753bb73906fd815420f857b61252aaad">llvm::AMDGPUMangledLibFunc::parseFuncName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a7c0ca54e69238594591bb95cefe84844">llvm::AMDGPUUnmangledLibFunc::parseFuncName</a> and <a href="#afdd154b90e347f7ef5fc8681543ebc86">setId</a>.</p>

</div>
</div>

### Name {#af97bf3cc52e6bbc6ff75ddd349faa795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPULibFuncImpl::Name</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#ae6bb0cb8a9e02a75f49701e0a16dc2a2">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#af5327d7c8e0462524384e3d2d27712e9">llvm::AMDGPUUnmangledLibFunc::AMDGPUUnmangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a88b37321dc57da4ae7feeeca1167c723">llvm::AMDGPUUnmangledLibFunc::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a344338cbe9ee0464d18d208b2f79c7ac">llvm::AMDGPUUnmangledLibFunc::mangle</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a753bb73906fd815420f857b61252aaad">llvm::AMDGPUMangledLibFunc::parseFuncName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunmangledlibfunc/#a7c0ca54e69238594591bb95cefe84844">llvm::AMDGPUUnmangledLibFunc::parseFuncName</a> and <a href="#ad783e6edf33f340d74a7b8ecde825ee6">setName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

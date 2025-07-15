---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machineverifier-cpp-/machineverifier/bbinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BBInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30088e5eff5118eb8b0d9a9c9d4def3f">BBInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1eedfc9b0913658a7d008d918ffebcb">addRequired</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd203c75c8a5023af20b5bdf23a23f0">addRequired</a> (const RegSet &amp;RS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6383cf41107989c0c8859f600ad16ecf">addRequired</a> (const RegMap &amp;RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d3f4b6e00638ec19ba44c6efcfa6dd">isLiveOut</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558fbc6485736983a15c6b578a17451a">reachable</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a0e8b816afd805c78ea6ce805e294c5c2">RegMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6c466b192e4e6ce4ac0f88a1ff408c">vregsLiveIn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a817eebb0935f04aae42afad79e30a3d6">RegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae244f4ada08e286ad4219e5c1059c4ed">regsKilled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a817eebb0935f04aae42afad79e30a3d6">RegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edb7457d24a8d9c58df780276bea365">regsLiveOut</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a817eebb0935f04aae42afad79e30a3d6">RegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee0a2825321483d53174c8e8e84036d">vregsPassed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a817eebb0935f04aae42afad79e30a3d6">RegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78d3d82256fc3b1b7bcd4812c65c8f7">vregsRequired</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9a7a6b12b82a177fe2fadb0c3aa51097">BlockSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa438e2355f9535e204713d84fa40c25">Preds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9a7a6b12b82a177fe2fadb0c3aa51097">BlockSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355df476c99ea83d0b29880448ba7aff">Succs</a></td>
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


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BBInfo() {#a30088e5eff5118eb8b0d9a9c9d4def3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::BBInfo ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRequired() {#ae1eedfc9b0913658a7d008d918ffebcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::addRequired (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a3edb7457d24a8d9c58df780276bea365">regsLiveOut</a> and <a href="#ae78d3d82256fc3b1b7bcd4812c65c8f7">vregsRequired</a>.</p>


<p>Referenced by <a href="#a6383cf41107989c0c8859f600ad16ecf">addRequired</a>, <a href="#a9bd203c75c8a5023af20b5bdf23a23f0">addRequired</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97f881f7a367863cbd154c3adb1477f2">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsRequired</a>.</p>

</div>
</div>

### addRequired() {#a9bd203c75c8a5023af20b5bdf23a23f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::addRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a817eebb0935f04aae42afad79e30a3d6">RegSet</a> &amp; RS)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#ae1eedfc9b0913658a7d008d918ffebcb">addRequired</a> and <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>.</p>

</div>
</div>

### addRequired() {#a6383cf41107989c0c8859f600ad16ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::addRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a0e8b816afd805c78ea6ce805e294c5c2">RegMap</a> &amp; RM)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#ae1eedfc9b0913658a7d008d918ffebcb">addRequired</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isLiveOut() {#ad7d3f4b6e00638ec19ba44c6efcfa6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::isLiveOut (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#a3edb7457d24a8d9c58df780276bea365">regsLiveOut</a> and <a href="#afee0a2825321483d53174c8e8e84036d">vregsPassed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Preds {#aaa438e2355f9535e204713d84fa40c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::Preds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a3cc52e45540d8251a2f942f68ea47fa3">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionBefore</a>.</p>

</div>
</div>

### reachable {#a558fbc6485736983a15c6b578a17451a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::reachable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ac34a220d0655748b7ad5a1b5d2994dec">anonymous{MachineVerifier.cpp}::MachineVerifier::markReachable</a>.</p>

</div>
</div>

### regsKilled {#ae244f4ada08e286ad4219e5c1059c4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsKilled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a91a98a9dff1a64d1c6ba9a9dc801cf72">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineBundleAfter</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad19536429e02ee5405f51a51bbb256cd">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionAfter</a>.</p>

</div>
</div>

### regsLiveOut {#a3edb7457d24a8d9c58df780276bea365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::regsLiveOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#ae1eedfc9b0913658a7d008d918ffebcb">addRequired</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a>, <a href="#ad7d3f4b6e00638ec19ba44c6efcfa6dd">isLiveOut</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad19536429e02ee5405f51a51bbb256cd">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionAfter</a>.</p>

</div>
</div>

### Succs {#a355df476c99ea83d0b29880448ba7aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::Succs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a3cc52e45540d8251a2f942f68ea47fa3">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionBefore</a>.</p>

</div>
</div>

### vregsLiveIn {#a9a6c466b192e4e6ce4ac0f88a1ff408c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegMap anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsLiveIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97f881f7a367863cbd154c3adb1477f2">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsRequired</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>.</p>

</div>
</div>

### vregsPassed {#afee0a2825321483d53174c8e8e84036d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsPassed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a990694380bae24a3a5b09b9a12f2e333">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsPassed</a> and <a href="#ad7d3f4b6e00638ec19ba44c6efcfa6dd">isLiveOut</a>.</p>

</div>
</div>

### vregsRequired {#ae78d3d82256fc3b1b7bcd4812c65c8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSet anonymous{MachineVerifier.cpp}::MachineVerifier::BBInfo::vregsRequired</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#ae1eedfc9b0913658a7d008d918ffebcb">addRequired</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97f881f7a367863cbd154c3adb1477f2">anonymous{MachineVerifier.cpp}::MachineVerifier::calcRegsRequired</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a3f673ecaaa953b4589aa7d0f5f2320bb">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveVariables</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad19536429e02ee5405f51a51bbb256cd">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionAfter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

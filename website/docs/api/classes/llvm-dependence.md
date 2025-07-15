---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dependence
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Dependence` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> - This class represents a dependence between two memory memory references in a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Dependence { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">llvm/Analysis/DependenceAnalysis.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a> - This class represents a dependence between two memory references in a function. <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f01170a5cd6f9e63cbd122b0c502c7">DependenceInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb3bcfb403e08fc367626fcf6deaf45">Dependence</a> (Instruction *Source, Instruction *Destination)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a> (Dependence &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41ff4f605166a3c85036938a1ad3925">~Dependence</a> ()=default</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6512797c8b118af9a18bd6ca613a54">operator=</a> (Dependence &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add64f4bc4fb47b10873cbc281c55c62e">getSrc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSrc - Returns the source instruction for this dependence. <a href="#add64f4bc4fb47b10873cbc281c55c62e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9c3ea9ecca5734fd90a2eea39cb4f5">getDst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDst - Returns the destination instruction for this dependence. <a href="#a1e9c3ea9ecca5734fd90a2eea39cb4f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7780f0bbd839374ff5fb91a239d9841">isInput</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isInput - Returns true if this is an input dependence. <a href="#ac7780f0bbd839374ff5fb91a239d9841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0919ea6f8754522d917a800777b0a25">isOutput</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOutput - Returns true if this is an output dependence. <a href="#ae0919ea6f8754522d917a800777b0a25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab889e3f9b0a2c1dc309904a7396898e0">isFlow</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFlow - Returns true if this is a flow (aka true) dependence. <a href="#ab889e3f9b0a2c1dc309904a7396898e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad294d5b65bbfccffde92318366908984">isAnti</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isAnti - Returns true if this is an anti dependence. <a href="#ad294d5b65bbfccffde92318366908984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a286333a4f60ad31ee7eb740ecd74a7">isOrdered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOrdered - Returns true if dependence is Output, Flow, or Anti <a href="#a2a286333a4f60ad31ee7eb740ecd74a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523a208f42d38f81203dbf4e30ac6e78">isUnordered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isUnordered - Returns true if dependence is <a href="/web-llvm/docs/api/classes/input">Input</a> <a href="#a523a208f42d38f81203dbf4e30ac6e78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add779d54108acc05e86ec6e9e63c4ae4">isLoopIndependent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLoopIndependent - Returns true if this is a loop-independent dependence. <a href="#add779d54108acc05e86ec6e9e63c4ae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c65e22ef4b0368ab040d1bd4ead382d">isConfused</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isConfused - Returns true if this dependence is confused (the compiler understands nothing and makes worst-case assumptions). <a href="#a5c65e22ef4b0368ab040d1bd4ead382d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886316cc195e479380f646a819da7889">isConsistent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isConsistent - Returns true if this dependence is consistent (occurs every time the source and destination are executed). <a href="#a886316cc195e479380f646a819da7889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9245aaf7bf6289a627d1ad933b9ca3e0">getLevels</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLevels - Returns the number of common loops surrounding the source and destination of the dependence. <a href="#a9245aaf7bf6289a627d1ad933b9ca3e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0112f0ebe61c7ca76ee9fae467556d10">getDirection</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDirection - Returns the direction associated with a particular level. <a href="#a0112f0ebe61c7ca76ee9fae467556d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c26161353ca8ce411c81f4232a94539">getDistance</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDistance - Returns the distance (or NULL) associated with a particular level. <a href="#a7c26161353ca8ce411c81f4232a94539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca93b667be55877570c831f7c347959">isDirectionNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the direction vector is negative. <a href="#adca93b667be55877570c831f7c347959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5fcbbcaedea4fa0dfcce6b1a14e396">normalize</a> (ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the direction vector is negative, normalize the direction vector to make it non-negative. <a href="#ace5fcbbcaedea4fa0dfcce6b1a14e396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bb8dd6f8f9f9e8283f953be6f1a3f8">isPeelFirst</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPeelFirst - Returns true if peeling the first iteration from this loop will break this dependence. <a href="#a02bb8dd6f8f9f9e8283f953be6f1a3f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca5c337fca64f7b9c13f5b02796faf6">isPeelLast</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPeelLast - Returns true if peeling the last iteration from this loop will break this dependence. <a href="#a8ca5c337fca64f7b9c13f5b02796faf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3dba62b3e54312c7cb84af34d00015">isSplitable</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSplitable - Returns true if splitting this loop will break the dependence. <a href="#a6e3dba62b3e54312c7cb84af34d00015">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876e212045ef6030b89358f07cb28c0e">isScalar</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isScalar - Returns true if a particular level is scalar; that is, if no subscript in the source or destination mention the induction variable associated with the loop at this level. <a href="#a876e212045ef6030b89358f07cb28c0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94cb1f0992b1739bdb957d16dac6f0e4">getNextPredecessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNextPredecessor - Returns the value of the NextPredecessor field. <a href="#a94cb1f0992b1739bdb957d16dac6f0e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb637be21b67ed3be0bfa90d217210ad">getNextSuccessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNextSuccessor - Returns the value of the NextSuccessor field. <a href="#adb637be21b67ed3be0bfa90d217210ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2389ae9427c7734844717dea2300db">setNextPredecessor</a> (const Dependence *pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setNextPredecessor - Sets the value of the NextPredecessor field. <a href="#aeb2389ae9427c7734844717dea2300db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ceabc5872a149fff3f84e6dc0725f3a">setNextSuccessor</a> (const Dependence *succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setNextSuccessor - Sets the value of the NextSuccessor field. <a href="#a2ceabc5872a149fff3f84e6dc0725f3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - For debugging purposes, dumps a dependence to OS. <a href="#aecb581fe2d522d3f1ab25c5e5c024928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954d04511d4bae43d51433ff53f94256">Src</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1beb1a8d83eefbbef34d7a3a0d8c4ca">NextPredecessor</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9845c89299175d35d9c09bee036567">NextSuccessor</a> = nullptr</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> - This class represents a dependence between two memory memory references in a function.</p>


<p>It contains minimal information and is used in the very common situation where the compiler is unable to determine anything beyond the existence of a dependence; that is, it represents a confused dependence (see also <a href="/web-llvm/docs/api/classes/llvm/fulldependence">FullDependence</a>). In most cases (for output, flow, and anti dependences), the dependence implies an ordering, where the source must precede the destination; in contrast, input dependences are unordered.</p>


<p>When a dependence graph is built, each <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> will be a member of the set of predecessor edges for its destination instruction and a set if successor edges for its source instruction. These sets are represented as singly-linked lists, with the "next" fields stored in the dependence itelf.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Friends

### DependenceInfo {#a32f01170a5cd6f9e63cbd122b0c502c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a32f01170a5cd6f9e63cbd122b0c502c7">DependenceInfo</a>.</p>


<p>Referenced by <a href="#a32f01170a5cd6f9e63cbd122b0c502c7">DependenceInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Dependence() {#abbb3bcfb403e08fc367626fcf6deaf45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Dependence::Dependence (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Source, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Destination)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>References <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a> and <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Dependence() {#a4c3f23d19aa97b3c23515aa8011ebdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Dependence::Dependence (<a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>.</p>


<p>Referenced by <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>, <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#a8988356819c51e6dfd3296fde1480ace">llvm::FullDependence::FullDependence</a>, <a href="#a94cb1f0992b1739bdb957d16dac6f0e4">getNextPredecessor</a>, <a href="#adb637be21b67ed3be0bfa90d217210ad">getNextSuccessor</a>, <a href="#a1f6512797c8b118af9a18bd6ca613a54">operator=</a>, <a href="#aeb2389ae9427c7734844717dea2300db">setNextPredecessor</a> and <a href="#a2ceabc5872a149fff3f84e6dc0725f3a">setNextSuccessor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Dependence() {#ac41ff4f605166a3c85036938a1ad3925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::Dependence::~Dependence ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a1f6512797c8b118af9a18bd6ca613a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Dependence &amp; llvm::Dependence::operator= (<a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aecb581fe2d522d3f1ab25c5e5c024928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Dependence::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - For debugging purposes, dumps a dependence to OS.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a4f1a62c9e41a8ccca8495db9118fa390">llvm::Dependence::DVEntry::ALL</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917ad4051c16e1d2336250f8e267c1e03281">llvm::Dependence::DVEntry::EQ</a>, <a href="#a0112f0ebe61c7ca76ee9fae467556d10">getDirection</a>, <a href="#a7c26161353ca8ce411c81f4232a94539">getDistance</a>, <a href="#a9245aaf7bf6289a627d1ad933b9ca3e0">getLevels</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a03e1c9598683e23868735e72b8caaabd">llvm::Dependence::DVEntry::GT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ad294d5b65bbfccffde92318366908984">isAnti</a>, <a href="#a5c65e22ef4b0368ab040d1bd4ead382d">isConfused</a>, <a href="#a886316cc195e479380f646a819da7889">isConsistent</a>, <a href="#ab889e3f9b0a2c1dc309904a7396898e0">isFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#af47bf37decca7e443848028fa880eb14">isInput</a>, <a href="#add779d54108acc05e86ec6e9e63c4ae4">isLoopIndependent</a>, <a href="#ae0919ea6f8754522d917a800777b0a25">isOutput</a>, <a href="#a02bb8dd6f8f9f9e8283f953be6f1a3f8">isPeelFirst</a>, <a href="#a8ca5c337fca64f7b9c13f5b02796faf6">isPeelLast</a>, <a href="#a876e212045ef6030b89358f07cb28c0e">isScalar</a>, <a href="#a6e3dba62b3e54312c7cb84af34d00015">isSplitable</a> and <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a5796b2f4edcf01eb52e88d01493f1d58">llvm::Dependence::DVEntry::LT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#aeff14a86a3c66da54488ee9634663cf7">llvm::FullDependence::normalize</a>.</p>

</div>
</div>

### getDirection() {#a0112f0ebe61c7ca76ee9fae467556d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::Dependence::getDirection (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDirection - Returns the direction associated with a particular level.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a88a52b6c1ad08a7be2e90a3723910917a4f1a62c9e41a8ccca8495db9118fa390">llvm::Dependence::DVEntry::ALL</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### getDistance() {#a7c26161353ca8ce411c81f4232a94539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const SCEV * llvm::Dependence::getDistance (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDistance - Returns the distance (or NULL) associated with a particular level.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### getDst() {#a1e9c3ea9ecca5734fd90a2eea39cb4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Dependence::getDst ()</td>
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

<p>getDst - Returns the destination instruction for this dependence.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### getLevels() {#a9245aaf7bf6289a627d1ad933b9ca3e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::Dependence::getLevels ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLevels - Returns the number of common loops surrounding the source and destination of the dependence.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### getNextPredecessor() {#a94cb1f0992b1739bdb957d16dac6f0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Dependence * llvm::Dependence::getNextPredecessor ()</td>
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

<p>getNextPredecessor - Returns the value of the NextPredecessor field.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>.</p>

</div>
</div>

### getNextSuccessor() {#adb637be21b67ed3be0bfa90d217210ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Dependence * llvm::Dependence::getNextSuccessor ()</td>
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

<p>getNextSuccessor - Returns the value of the NextSuccessor field.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>.</p>

</div>
</div>

### getSrc() {#add64f4bc4fb47b10873cbc281c55c62e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Dependence::getSrc ()</td>
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

<p>getSrc - Returns the source instruction for this dependence.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### isAnti() {#ad294d5b65bbfccffde92318366908984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Dependence::isAnti ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isAnti - Returns true if this is an anti dependence.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a> and <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a> and <a href="#a2a286333a4f60ad31ee7eb740ecd74a7">isOrdered</a>.</p>

</div>
</div>

### isConfused() {#a5c65e22ef4b0368ab040d1bd4ead382d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isConfused ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isConfused - Returns true if this dependence is confused (the compiler understands nothing and makes worst-case assumptions).</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isConsistent() {#a886316cc195e479380f646a819da7889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isConsistent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isConsistent - Returns true if this dependence is consistent (occurs every time the source and destination are executed).</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isDirectionNegative() {#adca93b667be55877570c831f7c347959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isDirectionNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the direction vector is negative.</p>


<p>A negative direction vector means Src and Dst are reversed in the actual program.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### isFlow() {#ab889e3f9b0a2c1dc309904a7396898e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Dependence::isFlow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isFlow - Returns true if this is a flow (aka true) dependence.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a> and <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a> and <a href="#a2a286333a4f60ad31ee7eb740ecd74a7">isOrdered</a>.</p>

</div>
</div>

### isInput() {#ac7780f0bbd839374ff5fb91a239d9841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Dependence::isInput ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isInput - Returns true if this is an input dependence.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a> and <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>


<p>Referenced by <a href="#a523a208f42d38f81203dbf4e30ac6e78">isUnordered</a>.</p>

</div>
</div>

### isLoopIndependent() {#add779d54108acc05e86ec6e9e63c4ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isLoopIndependent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLoopIndependent - Returns true if this is a loop-independent dependence.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isOrdered() {#a2a286333a4f60ad31ee7eb740ecd74a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Dependence::isOrdered ()</td>
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

<p>isOrdered - Returns true if dependence is Output, Flow, or Anti</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>References <a href="#ad294d5b65bbfccffde92318366908984">isAnti</a>, <a href="#ab889e3f9b0a2c1dc309904a7396898e0">isFlow</a> and <a href="#ae0919ea6f8754522d917a800777b0a25">isOutput</a>.</p>

</div>
</div>

### isOutput() {#ae0919ea6f8754522d917a800777b0a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Dependence::isOutput ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isOutput - Returns true if this is an output dependence.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>References <a href="#a9b5c8661e5974c589c88e57a1df853e4">Dst</a> and <a href="#a954d04511d4bae43d51433ff53f94256">Src</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a> and <a href="#a2a286333a4f60ad31ee7eb740ecd74a7">isOrdered</a>.</p>

</div>
</div>

### isPeelFirst() {#a02bb8dd6f8f9f9e8283f953be6f1a3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isPeelFirst (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPeelFirst - Returns true if peeling the first iteration from this loop will break this dependence.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isPeelLast() {#a8ca5c337fca64f7b9c13f5b02796faf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isPeelLast (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPeelLast - Returns true if peeling the last iteration from this loop will break this dependence.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isScalar() {#a876e212045ef6030b89358f07cb28c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Dependence::isScalar (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isScalar - Returns true if a particular level is scalar; that is, if no subscript in the source or destination mention the induction variable associated with the loop at this level.</p>

<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a>.</p>

</div>
</div>

### isSplitable() {#a6e3dba62b3e54312c7cb84af34d00015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::isSplitable (unsigned Level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSplitable - Returns true if splitting this loop will break the dependence.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aecb581fe2d522d3f1ab25c5e5c024928">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### isUnordered() {#a523a208f42d38f81203dbf4e30ac6e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Dependence::isUnordered ()</td>
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

<p>isUnordered - Returns true if dependence is <a href="/web-llvm/docs/api/classes/input">Input</a></p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#ac7780f0bbd839374ff5fb91a239d9841">isInput</a>.</p>

</div>
</div>

### normalize() {#ace5fcbbcaedea4fa0dfcce6b1a14e396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Dependence::normalize (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the direction vector is negative, normalize the direction vector to make it non-negative.</p>


<p>Normalization is done by reversing Src and Dst, plus reversing the dependence directions and distances in the vector.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### setNextPredecessor() {#aeb2389ae9427c7734844717dea2300db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Dependence::setNextPredecessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> * pred)</td>
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

<p>setNextPredecessor - Sets the value of the NextPredecessor field.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>References <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### setNextSuccessor() {#a2ceabc5872a149fff3f84e6dc0725f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Dependence::setNextSuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> * succ)</td>
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

<p>setNextSuccessor - Sets the value of the NextSuccessor field.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a4c3f23d19aa97b3c23515aa8011ebdb6">Dependence</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Dst {#a9b5c8661e5974c589c88e57a1df853e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Dependence::Dst</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#abbb3bcfb403e08fc367626fcf6deaf45">Dependence</a>, <a href="#a1e9c3ea9ecca5734fd90a2eea39cb4f5">getDst</a>, <a href="#ad294d5b65bbfccffde92318366908984">isAnti</a>, <a href="#ab889e3f9b0a2c1dc309904a7396898e0">isFlow</a>, <a href="#ac7780f0bbd839374ff5fb91a239d9841">isInput</a>, <a href="#ae0919ea6f8754522d917a800777b0a25">isOutput</a> and <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#aeff14a86a3c66da54488ee9634663cf7">llvm::FullDependence::normalize</a>.</p>

</div>
</div>

### Src {#a954d04511d4bae43d51433ff53f94256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::Dependence::Src</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#abbb3bcfb403e08fc367626fcf6deaf45">Dependence</a>, <a href="#add64f4bc4fb47b10873cbc281c55c62e">getSrc</a>, <a href="#ad294d5b65bbfccffde92318366908984">isAnti</a>, <a href="#ab889e3f9b0a2c1dc309904a7396898e0">isFlow</a>, <a href="#ac7780f0bbd839374ff5fb91a239d9841">isInput</a>, <a href="#ae0919ea6f8754522d917a800777b0a25">isOutput</a> and <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#aeff14a86a3c66da54488ee9634663cf7">llvm::FullDependence::normalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NextPredecessor {#ae1beb1a8d83eefbbef34d7a3a0d8c4ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Dependence* llvm::Dependence::NextPredecessor = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

### NextSuccessor {#aca9845c89299175d35d9c09bee036567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Dependence * llvm::Dependence::NextSuccessor = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">DependenceAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp">DependenceAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-symbolrewriter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{SymbolRewriter.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{SymbolRewriter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor">ExplicitRewriteDescriptor&lt;DT, ValueType, Get&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor">PatternRewriteDescriptor&lt;DT, ValueType, Get, Iterator&gt;</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2b993464270184ef14740fc52e9588">ExplicitRewriteFunctionDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor">ExplicitRewriteDescriptor</a>&lt; RewriteDescriptor::Type::Function, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>, &amp;Module::getFunction &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a rewrite for an explicitly named (function) symbol. <a href="#acd2b993464270184ef14740fc52e9588">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d817508e6c9f252a403031cd6380a30">ExplicitRewriteGlobalVariableDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor">ExplicitRewriteDescriptor</a>&lt; RewriteDescriptor::Type::GlobalVariable, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>, &amp;Module::getGlobalVariable &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a rewrite for an explicitly named (global variable) symbol. <a href="#a9d817508e6c9f252a403031cd6380a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93abb30a5ea2e6c5c44fa56897f4cd1e">ExplicitRewriteNamedAliasDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor">ExplicitRewriteDescriptor</a>&lt; RewriteDescriptor::Type::NamedAlias, <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a>, &amp;Module::getNamedAlias &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a rewrite for an explicitly named global alias. <a href="#a93abb30a5ea2e6c5c44fa56897f4cd1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9a5b185846f186f5013c465fe4133c7">PatternRewriteFunctionDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor">PatternRewriteDescriptor</a>&lt; RewriteDescriptor::Type::Function, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>, &amp;Module::getFunction, &amp;Module::functions &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a rewrite for a regular expression based pattern for functions. <a href="#ae9a5b185846f186f5013c465fe4133c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5820078ce53a3521ede4d80e8d949884">PatternRewriteGlobalVariableDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor">PatternRewriteDescriptor</a>&lt; RewriteDescriptor::Type::GlobalVariable, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>, &amp;Module::getGlobalVariable, &amp;Module::globals &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a rewrite for a global variable based upon a matching pattern. <a href="#a5820078ce53a3521ede4d80e8d949884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02599b3f9f64e3f19f868c8c36712507">PatternRewriteNamedAliasDescriptor</a> = <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor">PatternRewriteDescriptor</a>&lt; RewriteDescriptor::Type::NamedAlias, <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a>, &amp;Module::getNamedAlias, &amp;Module::aliases &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a02599b3f9f64e3f19f868c8c36712507">PatternRewriteNamedAliasDescriptor</a> - represents a rewrite for global aliases which match a given pattern. <a href="#a02599b3f9f64e3f19f868c8c36712507">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### ExplicitRewriteFunctionDescriptor {#acd2b993464270184ef14740fc52e9588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::ExplicitRewriteFunctionDescriptor = 
    ExplicitRewriteDescriptor&lt;RewriteDescriptor::Type::Function, Function,
                              &amp;Module::getFunction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a rewrite for an explicitly named (function) symbol.</p>


<p>Both the source function name and target function name of the transformation are explicitly spelt out.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### ExplicitRewriteGlobalVariableDescriptor {#a9d817508e6c9f252a403031cd6380a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::ExplicitRewriteGlobalVariableDescriptor = 
    ExplicitRewriteDescriptor&lt;RewriteDescriptor::Type::GlobalVariable,
                              GlobalVariable, &amp;Module::getGlobalVariable&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a rewrite for an explicitly named (global variable) symbol.</p>


<p>Both the source variable name and target variable name are spelt out. This applies only to module level variables.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### ExplicitRewriteNamedAliasDescriptor {#a93abb30a5ea2e6c5c44fa56897f4cd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::ExplicitRewriteNamedAliasDescriptor = 
    ExplicitRewriteDescriptor&lt;RewriteDescriptor::Type::NamedAlias, GlobalAlias,
                              &amp;Module::getNamedAlias&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a rewrite for an explicitly named global alias.</p>


<p>Both the source and target name are explicitly spelt out.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### PatternRewriteFunctionDescriptor {#ae9a5b185846f186f5013c465fe4133c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::PatternRewriteFunctionDescriptor = 
    PatternRewriteDescriptor&lt;RewriteDescriptor::Type::Function, Function,
                             &amp;Module::getFunction, &amp;Module::functions&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a rewrite for a regular expression based pattern for functions.</p>


<p>A pattern for the function name is provided and a transformation for that pattern to determine the target function name create the rewrite rule.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### PatternRewriteGlobalVariableDescriptor {#a5820078ce53a3521ede4d80e8d949884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::PatternRewriteGlobalVariableDescriptor = 
    PatternRewriteDescriptor&lt;RewriteDescriptor::Type::GlobalVariable,
                             GlobalVariable, &amp;Module::getGlobalVariable,
                             &amp;Module::globals&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a rewrite for a global variable based upon a matching pattern.</p>


<p>Each global variable matching the provided pattern will be transformed as described in the transformation pattern for the target. Applies only to module level variables.</p>


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### PatternRewriteNamedAliasDescriptor {#a02599b3f9f64e3f19f868c8c36712507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SymbolRewriter.cpp}::PatternRewriteNamedAliasDescriptor = 
    PatternRewriteDescriptor&lt;RewriteDescriptor::Type::NamedAlias, GlobalAlias,
                             &amp;Module::getNamedAlias, &amp;Module::aliases&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a02599b3f9f64e3f19f868c8c36712507">PatternRewriteNamedAliasDescriptor</a> - represents a rewrite for global aliases which match a given pattern.</p>


<p>The provided transformation will be applied to each of the matching names.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

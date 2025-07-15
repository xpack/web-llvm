---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BitmaskEnum.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cassert&gt;
#include &lt;type_traits&gt;
#include &lt;utility&gt;
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlforwardcompat-h">llvm/ADT/STLForwardCompat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/bitmaskenumdetail">BitmaskEnumDetail</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/is-bitmask-enum">is_bitmask_enum&lt;E, Enable&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traits class to determine whether an enum has a LLVM_BITMASK_LARGEST_ENUMERATOR enumerator. <a href="/web-llvm/docs/api/structs/llvm/is-bitmask-enum/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/is-bitmask-enum-0056a32b9ef926cb8b4f56b3acf01ac9">is_bitmask_enum&lt;E, std::enable_if_t&lt; sizeof(E::LLVM_BITMASK_LARGEST_ENUMERATOR) &gt;=0 &gt;&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/largest-bitmask-enum-bit-0056a32b9ef926cb8b4f56b3acf01ac9">largest_bitmask_enum_bit&lt;E, std::enable_if_t&lt; sizeof(E::LLVM_BITMASK_LARGEST_ENUMERATOR) &gt;=0 &gt;&gt;</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5467fafc9bd99ee2e38518ac3bea3a9d">LLVM_MARK_AS_BITMASK_ENUM</a>(LargestValue)&nbsp;&nbsp;&nbsp;  LLVM_BITMASK_LARGEST_ENUMERATOR = LargestValue</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_MARK_AS_BITMASK_ENUM lets you opt in an individual enum type so you can perform bitwise operations on it without putting static_cast everywhere. <a href="#a5467fafc9bd99ee2e38518ac3bea3a9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a43f81733f6f76bee7a0db9ff17da9d">LLVM_DECLARE_ENUM_AS_BITMASK</a>(Enum, LargestValue)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_DECLARE_ENUM_AS_BITMASK can be used to declare an enum type as a bit set, so that bitwise operation on such enum does not require static_cast. <a href="#a4a43f81733f6f76bee7a0db9ff17da9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f86495e0d13f14f9b22ccbda6ca2270">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE</a>()&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a2f86495e0d13f14f9b22ccbda6ca2270">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE()</a> pulls the operator overloads used by LLVM_MARK_AS_BITMASK_ENUM into the current namespace. <a href="#a2f86495e0d13f14f9b22ccbda6ca2270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Macro Definitions

### LLVM\_DECLARE\_ENUM\_AS\_BITMASK {#a4a43f81733f6f76bee7a0db9ff17da9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_DECLARE_ENUM_AS_BITMASK(Enum, LargestValue)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_DECLARE_ENUM_AS_BITMASK can be used to declare an enum type as a bit set, so that bitwise operation on such enum does not require static_cast.</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  template &lt;&gt; struct is_bitmask_enum&lt;Enum&gt; : std::true_type {};                \
  template &lt;&gt; struct largest_bitmask_enum_bit&lt;Enum&gt; {                          \
    static constexpr std::underlying_type_t&lt;Enum&gt; value = LargestValue;        \
  }
</div>
</dd>
</dl>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">enum MyEnum { E1 = 1, E2 = 2, E3 = 4, E4 = 8 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">LLVM_DECLARE_ENUM_AS_BITMASK(MyEnum, E4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">void Foo() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  MyEnum A = (E1 | E2) &amp; E3 ^ ~E4; // No static_cast</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>The second parameter to LLVM_DECLARE_ENUM_AS_BITMASK specifies the largest bit value of the enum type.</p>


<p>LLVM_DECLARE_ENUM_AS_BITMASK should be used in llvm namespace.</p>


<p>This a non-intrusive alternative for LLVM_MARK_AS_BITMASK_ENUM. It allows declaring more than one non-scoped enumerations as bitmask types in the same scope. Otherwise it provides the same functionality as LLVM_MARK_AS_BITMASK_ENUM.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h">BitmaskEnum.h</a>.</p>

</div>
</div>

### LLVM\_ENABLE\_BITMASK\_ENUMS\_IN\_NAMESPACE {#a2f86495e0d13f14f9b22ccbda6ca2270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE()&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a2f86495e0d13f14f9b22ccbda6ca2270">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE()</a> pulls the operator overloads used by LLVM_MARK_AS_BITMASK_ENUM into the current namespace.</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  using <a href="/web-llvm/docs/api/namespaces/llvm/bitmaskenumdetail/#a40fc6a6157fd6dc073230a96f3bf56b4">::llvm::BitmaskEnumDetail::operator~</a>;                                  \
  using ::llvm::BitmaskEnumDetail::operator|;                                  \
  using ::llvm::BitmaskEnumDetail::operator&amp;;                                  \
  using ::llvm::BitmaskEnumDetail::operator^;                                  \
  using ::llvm::BitmaskEnumDetail::operator&lt;&lt;;                                 \
  using ::llvm::BitmaskEnumDetail::operator&gt;&gt;;                                 \
  using ::llvm::BitmaskEnumDetail::operator|=;                                 \
  using ::llvm::BitmaskEnumDetail::operator&amp;=;                                 \
  using ::llvm::BitmaskEnumDetail::operator^=;                                 \
  using ::llvm::BitmaskEnumDetail::operator&lt;&lt;=;                                \
  using ::llvm::BitmaskEnumDetail::operator&gt;&gt;=;                                \
  /* Force a semicolon at the end of this macro. */                            \
  using <a href="/web-llvm/docs/api/namespaces/llvm/bitmaskenumdetail/#a35df90b2a21bb9cf7c36712bc206d523">::llvm::BitmaskEnumDetail::any</a>
</div>
</dd>
</dl>


<p>Suppose you have an enum foo::bar::MyEnum. Before using LLVM_MARK_AS_BITMASK_ENUM on MyEnum, you must put <a href="#a2f86495e0d13f14f9b22ccbda6ca2270">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE()</a> somewhere inside namespace foo or namespace foo::bar. This allows the relevant operator overloads to be found by ADL.</p>


<p>You don't need to use this macro in namespace llvm; it's done at the bottom of this file.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h">BitmaskEnum.h</a>.</p>

</div>
</div>

### LLVM\_MARK\_AS\_BITMASK\_ENUM {#a5467fafc9bd99ee2e38518ac3bea3a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_MARK_AS_BITMASK_ENUM(LargestValue)&nbsp;&nbsp;&nbsp;  LLVM_BITMASK_LARGEST_ENUMERATOR = LargestValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_MARK_AS_BITMASK_ENUM lets you opt in an individual enum type so you can perform bitwise operations on it without putting static_cast everywhere.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">enum MyEnum {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  E1 = 1, E2 = 2, E3 = 4, E4 = 8,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  LLVM_MARK_AS_BITMASK_ENUM(/* LargestValue = */ E4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">void Foo() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  MyEnum A = (E1 | E2) &amp; E3 ^ ~E4; // Look, ma: No static_cast!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Normally when you do a bitwise operation on an enum value, you get back an instance of the underlying type (e.g. int). But using this macro, bitwise ops on your enum will return you back instances of the enum. This is particularly useful for enums which represent a combination of flags.</p>


<p>The parameter to LLVM_MARK_AS_BITMASK_ENUM should be the largest individual value in your enum.</p>


<p>All of the enum's values must be non-negative.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h">BitmaskEnum.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

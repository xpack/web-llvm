---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/log-reader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `log_reader` Namespace



## Definition

<div class="doxyDefinition">
namespace log_reader { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/log-reader/tensorspec">TensorSpec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/log-reader/tensorvalue">TensorValue</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/log-reader/tensorvalue">TensorValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824cd3e05f3d3094a806870ea1ea5da9">read_tensor</a> (io.BufferedReader fs, TensorSpec ts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b90855a54de6f662b45732cb262314">pretty_print_tensor_value</a> (TensorValue tv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40242c357e077a78fbfb8fd4a61cf90">read_header</a> (io.BufferedReader f)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224d6d585cf78a7b3baeaa7474fffc13">read_one_observation</a> (Optional[str] context, str event_str, io.BufferedReader f, List[TensorSpec] tensor_specs, Optional[TensorSpec] score_spec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795f34462a51ea2794eb103b432ad61f">read_stream</a> (str fname)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a10719af7fe8bd112870799e9472d1">main</a> (args)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">dict</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17de637376c1a53d82da117294ba2e82">_element_types</a> = ...</td>
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




<pre><code>Reader for training log.

See lib/Analysis/TrainingLogger.cpp for a description of the format.
</code></pre>


<div class="doxySectionDef">

## Functions

### main() {#a00a10719af7fe8bd112870799e9472d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.main (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a> args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>References <a href="#a00a10719af7fe8bd112870799e9472d1">main</a>, <a href="#a14b90855a54de6f662b45732cb262314">pretty_print_tensor_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a> and <a href="#a795f34462a51ea2794eb103b432ad61f">read_stream</a>.</p>


<p>Referenced by <a href="#a00a10719af7fe8bd112870799e9472d1">main</a>.</p>

</div>
</div>

### pretty\_print\_tensor\_value() {#a14b90855a54de6f662b45732cb262314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.pretty_print_tensor_value (<a href="/web-llvm/docs/api/classes/log-reader/tensorvalue">TensorValue</a> tv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="#a00a10719af7fe8bd112870799e9472d1">main</a> and <a href="/web-llvm/docs/api/namespaces/interactive-host/#a0eded48c2eef46879e2f4d0fd284238b">interactive_host.run_interactive</a>.</p>

</div>
</div>

### read\_header() {#ab40242c357e077a78fbfb8fd4a61cf90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.read_header (io.BufferedReader f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Referenced by <a href="#a795f34462a51ea2794eb103b432ad61f">read_stream</a> and <a href="/web-llvm/docs/api/namespaces/interactive-host/#a0eded48c2eef46879e2f4d0fd284238b">interactive_host.run_interactive</a>.</p>

</div>
</div>

### read\_one\_observation() {#a224d6d585cf78a7b3baeaa7474fffc13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.read_one_observation (Optional context=[str], str event_str, io.BufferedReader f, List tensor_specs=[TensorSpec], Optional score_spec=[TensorSpec])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Reference <a href="#a824cd3e05f3d3094a806870ea1ea5da9">read_tensor</a>.</p>


<p>Referenced by <a href="#a795f34462a51ea2794eb103b432ad61f">read_stream</a> and <a href="/web-llvm/docs/api/namespaces/interactive-host/#a0eded48c2eef46879e2f4d0fd284238b">interactive_host.run_interactive</a>.</p>

</div>
</div>

### read\_stream() {#a795f34462a51ea2794eb103b432ad61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">log_reader.read_stream (str fname)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>References <a href="#ab40242c357e077a78fbfb8fd4a61cf90">read_header</a> and <a href="#a224d6d585cf78a7b3baeaa7474fffc13">read_one_observation</a>.</p>


<p>Referenced by <a href="#a00a10719af7fe8bd112870799e9472d1">main</a>.</p>

</div>
</div>

### read\_tensor() {#a824cd3e05f3d3094a806870ea1ea5da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName"> TensorValue log_reader.read_tensor (io.BufferedReader fs, <a href="/web-llvm/docs/api/classes/log-reader/tensorspec">TensorSpec</a> ts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>


<p>Referenced by <a href="#a224d6d585cf78a7b3baeaa7474fffc13">read_one_observation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### \_element\_types {#a17de637376c1a53d82da117294ba2e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dict log_reader._element_types</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=  {
    "float": ctypes.c_float,
    "double": ctypes.c_double,
    "int8_t": ctypes.c_int8,
    "uint8_t": ctypes.c_uint8,
    "int16_t": ctypes.c_int16,
    "uint16_t": ctypes.c_uint16,
    "int32_t": ctypes.c_int32,
    "uint32_t": ctypes.c_uint32,
    "int64_t": ctypes.c_int64,
    "uint64_t": ctypes.c_uint64,
}
</div>
</dd>
</dl>

<p>Definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/log-reader-py">log_reader.py</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

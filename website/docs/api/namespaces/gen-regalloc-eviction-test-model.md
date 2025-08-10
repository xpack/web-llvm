---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/gen-regalloc-eviction-test-model
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `gen-regalloc-eviction-test-model` Namespace



## Definition

<div class="doxyDefinition">
namespace gen-regalloc-eviction-test-model { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4baaaa4d1082b1e375b64fb4d12737">get_input_signature</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ab24b1a465e259a56ea4edb4c59fc4">get_output_spec_path</a> (path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc0794619dce658c82bf5f6b020a2ab">build_mock_model</a> (path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78793359f0fed5ee5638f1a79bd47e5">main</a> (argv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">str</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765c28b3d993a71c45adfe8b3c5e26fa">POLICY_DECISION_LABEL</a> =  "index_to_evict"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">str</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa291f0a3b725d73709dc1aa76bba66c9">POLICY_OUTPUT_SPEC</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">list</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dd7a477a1537c5be21e14c06e70110">PER_REGISTER_FEATURE_LIST</a> =  ["mask"]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819fd11156492eaed2497d8bd0ea90a2">NUM_REGISTERS</a> =  33</td>
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


<div class="doxySectionDef">

## Functions

### build\_mock\_model() {#aebc0794619dce658c82bf5f6b020a2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gen-regalloc-eviction-test-model.build_mock_model (path path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">





<pre><code>Build and save the mock model with the given signature.
</code></pre>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>


<p>References <a href="#a9d4baaaa4d1082b1e375b64fb4d12737">get_input_signature</a>, <a href="#a19ab24b1a465e259a56ea4edb4c59fc4">get_output_spec_path</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="#aa78793359f0fed5ee5638f1a79bd47e5">main</a>.</p>

</div>
</div>

### get\_input\_signature() {#a9d4baaaa4d1082b1e375b64fb4d12737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gen-regalloc-eviction-test-model.get_input_signature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">





<pre><code>Returns (time_step_spec, action_spec) for LLVM register allocation.
</code></pre>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>


<p>Referenced by <a href="#aebc0794619dce658c82bf5f6b020a2ab">build_mock_model</a>.</p>

</div>
</div>

### get\_output\_spec\_path() {#a19ab24b1a465e259a56ea4edb4c59fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gen-regalloc-eviction-test-model.get_output_spec_path (path path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>


<p>Referenced by <a href="#aebc0794619dce658c82bf5f6b020a2ab">build_mock_model</a>.</p>

</div>
</div>

### main() {#aa78793359f0fed5ee5638f1a79bd47e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gen-regalloc-eviction-test-model.main (argv argv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>


<p>References <a href="#aebc0794619dce658c82bf5f6b020a2ab">build_mock_model</a> and <a href="#aa78793359f0fed5ee5638f1a79bd47e5">main</a>.</p>


<p>Referenced by <a href="#aa78793359f0fed5ee5638f1a79bd47e5">main</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NUM\_REGISTERS {#a819fd11156492eaed2497d8bd0ea90a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int gen-regalloc-eviction-test-model.NUM_REGISTERS =  33</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>

</div>
</div>

### PER\_REGISTER\_FEATURE\_LIST {#a80dd7a477a1537c5be21e14c06e70110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">list gen-regalloc-eviction-test-model.PER_REGISTER_FEATURE_LIST =  ["mask"]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>

</div>
</div>

### POLICY\_DECISION\_LABEL {#a765c28b3d993a71c45adfe8b3c5e26fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">str gen-regalloc-eviction-test-model.POLICY_DECISION_LABEL =  "index_to_evict"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 10 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>

</div>
</div>

### POLICY\_OUTPUT\_SPEC {#aa291f0a3b725d73709dc1aa76bba66c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">str gen-regalloc-eviction-test-model.POLICY_OUTPUT_SPEC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=  """
[
    {
        "logging_name": "index_to_evict",
        "tensor_spec": {
            "name": "StatefulPartitionedCall",
            "port": 0,
            "type": "int64_t",
            "shape": [
                1
            ]
        }
    }
]
"""
</div>
</dd>
</dl>

<p>Definition at line 11 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/gen-regalloc-eviction-test-model-py">gen-regalloc-eviction-test-model.py</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

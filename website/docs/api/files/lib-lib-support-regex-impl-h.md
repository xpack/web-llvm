---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regex-impl-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `regex_impl.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;sys/types.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm-regmatch-t">llvm_regmatch_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm-regex">llvm_regex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">off_t <a href="#ae931ea6606e024ac6a6e0149844605cc">llvm_regoff_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/llvm-regex">llvm_regex</a> <a href="#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cce3d0a9a55a5831788470bd2ef268">llvm_regcomp</a> (llvm_regex_t *, const char *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e632f84f9002c2619c902788dae5b97">llvm_regerror</a> (int, const llvm_regex_t *, char *, size_t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> (const llvm_regex_t *, const char *, size_t, llvm_regmatch_t[], int)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a> (llvm_regex_t *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0665f8b90af5f30c518451a34a94e0aa">llvm_strlcpy</a> (char *dst, const char *src, size_t siz)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c264ea8b3d5afe67d7a1ecc46b4d31">REG_BASIC</a>&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc31e6da9b77e09ea62b4544ac4767f">REG_EXTENDED</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3e7b1d5bc9c2d278a544fe9b61b67a">REG_ICASE</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb835c7fe6f1673fc0efeff0064510ab">REG_NOSUB</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab678ef3b27bf7de2fb82c79cb2cd9d8a">REG_NEWLINE</a>&nbsp;&nbsp;&nbsp;10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6330cb5b93bbe64df6c63d57bbd866b5">REG_NOSPEC</a>&nbsp;&nbsp;&nbsp;20</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95142205890c3ac8dc12e5850cb0e946">REG_PEND</a>&nbsp;&nbsp;&nbsp;40</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4eb1f7553209185de343c875ca5142">REG_DUMP</a>&nbsp;&nbsp;&nbsp;200</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183aab34192b1bdc18a56e84759aa210">REG_NOMATCH</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8233bd7398fdb236c8dadf7abebb8a3">REG_ECOLLATE</a>&nbsp;&nbsp;&nbsp;3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d4f054978e6b70c2672145435a7917">REG_ECTYPE</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c04bdcb329fb937154b2b47b2c0c2e0">REG_EESCAPE</a>&nbsp;&nbsp;&nbsp;5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93635e62856bab30bab8d0bc400ff07d">REG_ESUBREG</a>&nbsp;&nbsp;&nbsp;6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>&nbsp;&nbsp;&nbsp;7</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad059816a7c4eb7e2193aadc66627a976">REG_EPAREN</a>&nbsp;&nbsp;&nbsp;8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0065762ae9d5301a00eddb6242f104b">REG_EBRACE</a>&nbsp;&nbsp;&nbsp;9</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4693ad3584b57edf162fa492f85c16f">REG_BADBR</a>&nbsp;&nbsp;&nbsp;10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92147e11843057bc3c9a5b2a2f682b14">REG_ERANGE</a>&nbsp;&nbsp;&nbsp;11</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>&nbsp;&nbsp;&nbsp;12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377356d91031028d3c2d6960b6fb3ac0">REG_BADRPT</a>&nbsp;&nbsp;&nbsp;13</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a>&nbsp;&nbsp;&nbsp;14</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284ab151886dcb8b211f21a8a0d36d78">REG_ASSERT</a>&nbsp;&nbsp;&nbsp;15</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dba69255d33bbff71dc102cd9d5477e">REG_INVARG</a>&nbsp;&nbsp;&nbsp;16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527188d8a22e439dd6dfa7d909815611">REG_ATOI</a>&nbsp;&nbsp;&nbsp;255	/* <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> to number (!) */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2cc83a1e03c9821465885213d5af5b">REG_ITOA</a>&nbsp;&nbsp;&nbsp;0400	/* <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a> number to <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> (!) */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ca15a79530976f6d4ef90326c46858">REG_NOTBOL</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d97d85ef86123060a845723d28a92cb">REG_NOTEOL</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343ef97b721e94f5cb1a8d2e742132b1">REG_STARTEND</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd455037c8cbd9070d089f41a8f6873">REG_TRACE</a>&nbsp;&nbsp;&nbsp;00400	/* tracing of <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a> */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c9402d70d5e7b84901663934bbe901">REG_LARGE</a>&nbsp;&nbsp;&nbsp;01000	/* force large representation */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5523d1d88d3c94e9d929995bf7c20e0">REG_BACKR</a>&nbsp;&nbsp;&nbsp;02000	/* force <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a> of backref code */</td>
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

## Typedefs

### llvm\_regex\_t {#a14d8a63433f444e7352b4e931cf33335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct llvm_regex llvm_regex_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### llvm\_regoff\_t {#ae931ea6606e024ac6a6e0149844605cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef off_t llvm_regoff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### llvm\_regcomp() {#a72cce3d0a9a55a5831788470bd2ef268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm_regcomp (<a href="#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * pattern, int cflags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a>, <a href="/web-llvm/docs/api/structs/re-guts/#a120902614290b8531ce62482aa5e43d0">re_guts::cflags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>, <a href="#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a4d75c71d09855c3c47f35622b289316f">NPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a434ef202369d0ddf2def41bfeaad210e">OEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aec78e7a9e90a406a56f859ee456e8eae">OUT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a86427d4d576dd8585a539946c3d662b0">p_str</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#af5da3516ebe39b7fe40315175d49b55a">llvm_regex::re_endp</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#ab7b9279f0acdb26e438298369f121641">llvm_regex::re_nsub</a>, <a href="#a284ab151886dcb8b211f21a8a0d36d78">REG_ASSERT</a>, <a href="#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>, <a href="#a5fc31e6da9b77e09ea62b4544ac4767f">REG_EXTENDED</a>, <a href="#a5dba69255d33bbff71dc102cd9d5477e">REG_INVARG</a>, <a href="#a6330cb5b93bbe64df6c63d57bbd866b5">REG_NOSPEC</a>, <a href="#a95142205890c3ac8dc12e5850cb0e946">REG_PEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### llvm\_regerror() {#a9e632f84f9002c2619c902788dae5b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm_regerror (int errcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, char * errbuf, size_t errbuf_size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c">regerror.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/rerr/#a0bbc574398805ac6226a74745d8a8215">rerr::code</a>, <a href="/web-llvm/docs/api/structs/rerr/#a00db6e0c7d6449af27fff2afdb4155ea">rerr::explain</a>, <a href="#a0665f8b90af5f30c518451a34a94e0aa">llvm_strlcpy</a>, <a href="/web-llvm/docs/api/structs/rerr/#a2f69e340c9f6404032c5f9d5ea84245b">rerr::name</a>, <a href="#a527188d8a22e439dd6dfa7d909815611">REG_ATOI</a>, <a href="#a2a2cc83a1e03c9821465885213d5af5b">REG_ITOA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#af481b7e4615b89b40883ff6f7f60bafd">regatoi</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#a3163e0fa575d4c1b102ac71ea9454896">rerrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-regex-cpp-/#a2cf0de01ea6bd871ff2bc908265cb0f0">anonymous{Regex.cpp}::RegexErrorToString</a>.</p>

</div>
</div>

### llvm\_regexec() {#a91460c195c399d42fa14fbb37d0465a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm_regexec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * string, size_t nmatch, <a href="/web-llvm/docs/api/structs/llvm-regmatch-t">llvm_regmatch_t</a> pmatch=[], int eflags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c/#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>, <a href="#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a>, <a href="#a16c9402d70d5e7b84901663934bbe901">REG_LARGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c/#a602d88f3fdc69402056326f5b0215216">states1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>.</p>

</div>
</div>

### llvm\_regfree() {#a5b067957e932003b295ff3a8bbffe882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_regfree (<a href="#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regfree-c">regfree.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a> and <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a4b32acda8c0843ee5a68ebccba4ad993">llvm::Regex::~Regex</a>.</p>

</div>
</div>

### llvm\_strlcpy() {#a0665f8b90af5f30c518451a34a94e0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm_strlcpy (char * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * src, size_t siz)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regstrlcpy-c">regstrlcpy.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### REG\_ASSERT {#a284ab151886dcb8b211f21a8a0d36d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ASSERT&nbsp;&nbsp;&nbsp;15</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### REG\_ATOI {#a527188d8a22e439dd6dfa7d909815611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ATOI&nbsp;&nbsp;&nbsp;255	/* <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> to number (!) */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a>.</p>

</div>
</div>

### REG\_BACKR {#aa5523d1d88d3c94e9d929995bf7c20e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_BACKR&nbsp;&nbsp;&nbsp;02000	/* force <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a> of backref code */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_BADBR {#aa4693ad3584b57edf162fa492f85c16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_BADBR&nbsp;&nbsp;&nbsp;10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_BADPAT {#ad7e13616a54be821d6b686d8b2587401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_BADPAT&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#aac844880235ca7d00251aca1cc406c45">llvm::Regex::Regex</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a79c76bd33fa9d47ce2ed57c301e0c919">llvm::Regex::Regex</a>.</p>

</div>
</div>

### REG\_BADRPT {#a377356d91031028d3c2d6960b6fb3ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_BADRPT&nbsp;&nbsp;&nbsp;13</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_BASIC {#ac9c264ea8b3d5afe67d7a1ecc46b4d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_BASIC&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_DUMP {#a0f4eb1f7553209185de343c875ca5142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_DUMP&nbsp;&nbsp;&nbsp;200</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_EBRACE {#ad0065762ae9d5301a00eddb6242f104b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EBRACE&nbsp;&nbsp;&nbsp;9</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_EBRACK {#a1e0ef4e0e9d4b184f1b21285cee16c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EBRACK&nbsp;&nbsp;&nbsp;7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### REG\_ECOLLATE {#ac8233bd7398fdb236c8dadf7abebb8a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ECOLLATE&nbsp;&nbsp;&nbsp;3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### REG\_ECTYPE {#a16d4f054978e6b70c2672145435a7917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ECTYPE&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### REG\_EESCAPE {#a3c04bdcb329fb937154b2b47b2c0c2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EESCAPE&nbsp;&nbsp;&nbsp;5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_EMPTY {#ab974b0d779831c3f7ba76a70748d7e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EMPTY&nbsp;&nbsp;&nbsp;14</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a86427d4d576dd8585a539946c3d662b0">p_str</a>.</p>

</div>
</div>

### REG\_EPAREN {#ad059816a7c4eb7e2193aadc66627a976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EPAREN&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_ERANGE {#a92147e11843057bc3c9a5b2a2f682b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ERANGE&nbsp;&nbsp;&nbsp;11</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### REG\_ESPACE {#ae0ee85477e8756f1cf2d7fab21e56235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ESPACE&nbsp;&nbsp;&nbsp;12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ada80fc7b6139b088f956ab9200bd15dd">allocset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a>.</p>

</div>
</div>

### REG\_ESUBREG {#a93635e62856bab30bab8d0bc400ff07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ESUBREG&nbsp;&nbsp;&nbsp;6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REG\_EXTENDED {#a5fc31e6da9b77e09ea62b4544ac4767f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_EXTENDED&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### REG\_ICASE {#a0c3e7b1d5bc9c2d278a544fe9b61b67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ICASE&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### REG\_INVARG {#a5dba69255d33bbff71dc102cd9d5477e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_INVARG&nbsp;&nbsp;&nbsp;16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### REG\_ITOA {#a2a2cc83a1e03c9821465885213d5af5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_ITOA&nbsp;&nbsp;&nbsp;0400	/* <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a> number to <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> (!) */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a>.</p>

</div>
</div>

### REG\_LARGE {#a16c9402d70d5e7b84901663934bbe901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_LARGE&nbsp;&nbsp;&nbsp;01000	/* force large representation */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>.</p>

</div>
</div>

### REG\_NEWLINE {#ab678ef3b27bf7de2fb82c79cb2cd9d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NEWLINE&nbsp;&nbsp;&nbsp;10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### REG\_NOMATCH {#a183aab34192b1bdc18a56e84759aa210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NOMATCH&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>.</p>

</div>
</div>

### REG\_NOSPEC {#a6330cb5b93bbe64df6c63d57bbd866b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NOSPEC&nbsp;&nbsp;&nbsp;20</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### REG\_NOSUB {#abb835c7fe6f1673fc0efeff0064510ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NOSUB&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_NOTBOL {#aa0ca15a79530976f6d4ef90326c46858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NOTBOL&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_NOTEOL {#a9d97d85ef86123060a845723d28a92cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_NOTEOL&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

### REG\_PEND {#a95142205890c3ac8dc12e5850cb0e946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_PEND&nbsp;&nbsp;&nbsp;40</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### REG\_STARTEND {#a343ef97b721e94f5cb1a8d2e742132b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_STARTEND&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>.</p>

</div>
</div>

### REG\_TRACE {#a1cd455037c8cbd9070d089f41a8f6873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REG_TRACE&nbsp;&nbsp;&nbsp;00400	/* tracing of <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a> */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

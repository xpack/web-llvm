---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regex2-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `regex2.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h">regutils.h</a>"
#include &lt;stddef.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/cset">cset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/re-guts">re_guts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned long <a href="#a06b705baf08297be667616dcfd9b63a6">sop</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">long <a href="#a1934207945a1bf71e1355e13cebc601a">sopno</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned char <a href="#af50ea19ede389706da4da6fd07f34d89">cat_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>&nbsp;&nbsp;&nbsp;((('r'^0200)&lt;&lt;8) | 'e')</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca404b4f6aece67469934ba024786a19">OPRMASK</a>&nbsp;&nbsp;&nbsp;0xf8000000LU</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf3d548b93b9e2214469a0555628464">OPDMASK</a>&nbsp;&nbsp;&nbsp;0x07ffffffLU</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>&nbsp;&nbsp;&nbsp;((unsigned)27)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4408501bd0122c5686327ce657853de">OP</a>(n)&nbsp;&nbsp;&nbsp;((n)&amp;<a href="#aca404b4f6aece67469934ba024786a19">OPRMASK</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eaed4c74d1e8101dbe98aa9bb336697">OPND</a>(n)&nbsp;&nbsp;&nbsp;((n)&amp;<a href="#a2cf3d548b93b9e2214469a0555628464">OPDMASK</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba860196419d979bad27253aeadb088d">SOP</a>(op, opnd)&nbsp;&nbsp;&nbsp;((<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>)|(opnd))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434ef202369d0ddf2def41bfeaad210e">OEND</a>&nbsp;&nbsp;&nbsp;(1LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* endmarker	-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d1c317420932112aa9e171d754811f">OCHAR</a>&nbsp;&nbsp;&nbsp;(2LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* character	unsigned char		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2228fd86a118c059a40aa7906b7b9f75">OBOL</a>&nbsp;&nbsp;&nbsp;(3LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* left anchor	-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64088e1d592688e933aaf055bada3212">OEOL</a>&nbsp;&nbsp;&nbsp;(4LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* right anchor	-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88ba7651db72b3ffcae8c995e2e908e">OANY</a>&nbsp;&nbsp;&nbsp;(5LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* .		-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac639b74f02e71b7e9b4e6179afc8b6f">OANYOF</a>&nbsp;&nbsp;&nbsp;(6LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* [...]	set number		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13f928297b563a52fe41e5fb1cc29a5">OBACK_</a>&nbsp;&nbsp;&nbsp;(7LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin \d	paren number		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe00fc485ef6e08c459df2f283fa5d9f">O_BACK</a>&nbsp;&nbsp;&nbsp;(8LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end \d	paren number		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a>&nbsp;&nbsp;&nbsp;(9LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* + prefix	fwd to suffix		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab259df0d57bb496a9d9614b9a6eacc8e">O_PLUS</a>&nbsp;&nbsp;&nbsp;(10LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* + suffix	back to prefix		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa9106fa97c3f33abc44db4f2a4f04a">OQUEST_</a>&nbsp;&nbsp;&nbsp;(11LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* ? prefix	fwd to suffix		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909bd2030d6527ad02f8bf552deec559">O_QUEST</a>&nbsp;&nbsp;&nbsp;(12LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* ? suffix	back to prefix		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68656a8c7cdec0a5e6112976802801fd">OLPAREN</a>&nbsp;&nbsp;&nbsp;(13LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* (		fwd to )		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad105523f8dbc7a2b1a0f6e98bff80ca4">ORPAREN</a>&nbsp;&nbsp;&nbsp;(14LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* )		back to (		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3540bd5c66f3147b883585e722d658bf">OCH_</a>&nbsp;&nbsp;&nbsp;(15LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin choice	fwd to <a href="#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85671ff22b1810567138bbcba708004">OOR1</a>&nbsp;&nbsp;&nbsp;(16LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* | pt. 1	back to OOR1 or <a href="#a3540bd5c66f3147b883585e722d658bf">OCH_</a>	*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>&nbsp;&nbsp;&nbsp;(17LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* | pt. 2	fwd to OOR2 or <a href="#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>	*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>&nbsp;&nbsp;&nbsp;(18LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end choice	back to <a href="#af85671ff22b1810567138bbcba708004">OOR1</a>		*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b67f8af6085cd377b776d876fbf08f5">OBOW</a>&nbsp;&nbsp;&nbsp;(19LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin word	-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac736e994358a7ca5c854cec2e689de2d">OEOW</a>&nbsp;&nbsp;&nbsp;(20LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end word	-			*/</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d21b10d07ea5a414f35de71fb5891d5">CHadd</a>(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] |= (cs)-&gt;mask, (cs)-&gt;hash += (c))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e39f78dc00de8dad42ae166aab07c05">CHsub</a>(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] &amp;= ~(cs)-&gt;mask, (cs)-&gt;hash -= (c))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1db32adfba101e49e40979db85943b3">CHIN</a>(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] &amp; (cs)-&gt;mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6583f0e5d8fd98cce75e9b5902f04a">MCadd</a>(p, cs, cp)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a>(p, cs, cp)	/* <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>() internal fns */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e13885061da4ee63c6410539798147">MCsub</a>(p, cs, cp)&nbsp;&nbsp;&nbsp;mcsub(p, cs, cp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb36bd9886d9d7f6e408428ccd07bef">MCin</a>(p, cs, cp)&nbsp;&nbsp;&nbsp;mcin(p, cs, cp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>&nbsp;&nbsp;&nbsp;((('R'^0200)&lt;&lt;8)|'<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>')</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87eb741ccad21cee1dc3830ca3f06a90">USEBOL</a>&nbsp;&nbsp;&nbsp;01	/* used ^ */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f50dd10938b851f6d38b7131e2ddd5">USEEOL</a>&nbsp;&nbsp;&nbsp;02	/* used $ */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a>&nbsp;&nbsp;&nbsp;04	/* something wrong */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec78e7a9e90a406a56f859ee456e8eae">OUT</a>&nbsp;&nbsp;&nbsp;(CHAR_MAX+1)	/* a non-character value */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc37963c8802906d559ffaf37aeda48">ISWORD</a>(c)&nbsp;&nbsp;&nbsp;(isalnum(c&amp;0xff) || (c) == '<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>')</td>
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

### cat\_t {#af50ea19ede389706da4da6fd07f34d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned char cat_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### sop {#a06b705baf08297be667616dcfd9b63a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned long sop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### sopno {#a1934207945a1bf71e1355e13cebc601a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef long sopno</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CHadd {#a6d21b10d07ea5a414f35de71fb5891d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHadd(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] |= (cs)-&gt;mask, (cs)-&gt;hash += (c))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a5782473066b8c574e25e16bd8a9ed067">p_b_eclass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### CHIN {#aa1db32adfba101e49e40979db85943b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHIN(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] &amp; (cs)-&gt;mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#afc1d8df71f0b5f0795df5212acfd57c9">firstch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a5933b7beb88db01c7671918d5e75a53c">freezeset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab04fc18d5a9bd2a4fc001ec92cc28a93">nch</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### CHsub {#a0e39f78dc00de8dad42ae166aab07c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHsub(cs, c)&nbsp;&nbsp;&nbsp;((cs)-&gt;ptr[(<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#af3307af5922c72924a837559c801a8a4">uch</a>)(c)] &amp;= ~(cs)-&gt;mask, (cs)-&gt;hash -= (c))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#af1b35f4d10e296aa74c965da8031ed26">freeset</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### ISWORD {#aebc37963c8802906d559ffaf37aeda48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISWORD(c)&nbsp;&nbsp;&nbsp;(isalnum(c&amp;0xff) || (c) == '<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>')</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### MAGIC1 {#ac77db84cf42ba546550a69ac744c14ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAGIC1&nbsp;&nbsp;&nbsp;((('r'^0200)&lt;&lt;8) | 'e')</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>.</p>

</div>
</div>

### MAGIC2 {#ade86ed2c7955ab1d3b4b4d84f7df8524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAGIC2&nbsp;&nbsp;&nbsp;((('R'^0200)&lt;&lt;8)|'<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>')</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>.</p>

</div>
</div>

### MCadd {#abf6583f0e5d8fd98cce75e9b5902f04a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCadd(p, cs, cp)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a>(p, cs, cp)	/* <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>() internal fns */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>.</p>

</div>
</div>

### MCin {#aabb36bd9886d9d7f6e408428ccd07bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCin(p, cs, cp)&nbsp;&nbsp;&nbsp;mcin(p, cs, cp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### MCsub {#a56e13885061da4ee63c6410539798147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCsub(p, cs, cp)&nbsp;&nbsp;&nbsp;mcsub(p, cs, cp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### O\_BACK {#abe00fc485ef6e08c459df2f283fa5d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define O_BACK&nbsp;&nbsp;&nbsp;(8LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end \d	paren number		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### O\_CH {#a1c30d83b5b72b81505f486ec816f7f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define O_CH&nbsp;&nbsp;&nbsp;(18LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end choice	back to <a href="#af85671ff22b1810567138bbcba708004">OOR1</a>		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### O\_PLUS {#ab259df0d57bb496a9d9614b9a6eacc8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define O_PLUS&nbsp;&nbsp;&nbsp;(10LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* + suffix	back to prefix		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### O\_QUEST {#a909bd2030d6527ad02f8bf552deec559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define O_QUEST&nbsp;&nbsp;&nbsp;(12LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* ? suffix	back to prefix		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### OANY {#af88ba7651db72b3ffcae8c995e2e908e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OANY&nbsp;&nbsp;&nbsp;(5LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* .		-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### OANYOF {#aac639b74f02e71b7e9b4e6179afc8b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OANYOF&nbsp;&nbsp;&nbsp;(6LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* [...]	set number		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### OBACK\_ {#ac13f928297b563a52fe41e5fb1cc29a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OBACK_&nbsp;&nbsp;&nbsp;(7LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin \d	paren number		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### OBOL {#a2228fd86a118c059a40aa7906b7b9f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OBOL&nbsp;&nbsp;&nbsp;(3LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* left anchor	-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### OBOW {#a6b67f8af6085cd377b776d876fbf08f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OBOW&nbsp;&nbsp;&nbsp;(19LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin word	-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### OCH\_ {#a3540bd5c66f3147b883585e722d658bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OCH_&nbsp;&nbsp;&nbsp;(15LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* begin choice	fwd to <a href="#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### OCHAR {#a54d1c317420932112aa9e171d754811f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OCHAR&nbsp;&nbsp;&nbsp;(2LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* character	unsigned char		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a72709d6823c4bd388ed9113242119a9b">ordinary</a>.</p>

</div>
</div>

### OEND {#a434ef202369d0ddf2def41bfeaad210e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OEND&nbsp;&nbsp;&nbsp;(1LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* endmarker	-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a>.</p>

</div>
</div>

### OEOL {#a64088e1d592688e933aaf055bada3212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OEOL&nbsp;&nbsp;&nbsp;(4LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* right anchor	-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### OEOW {#ac736e994358a7ca5c854cec2e689de2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OEOW&nbsp;&nbsp;&nbsp;(20LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* end word	-			*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### OLPAREN {#a68656a8c7cdec0a5e6112976802801fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OLPAREN&nbsp;&nbsp;&nbsp;(13LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* (		fwd to )		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### OOR1 {#af85671ff22b1810567138bbcba708004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OOR1&nbsp;&nbsp;&nbsp;(16LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* | pt. 1	back to OOR1 or <a href="#a3540bd5c66f3147b883585e722d658bf">OCH_</a>	*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### OOR2 {#a3af4f4635fa6eb5d9030afce3f795b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OOR2&nbsp;&nbsp;&nbsp;(17LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* | pt. 2	fwd to OOR2 or <a href="#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>	*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### OP {#af4408501bd0122c5686327ce657853de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OP(n)&nbsp;&nbsp;&nbsp;((n)&amp;<a href="#aca404b4f6aece67469934ba024786a19">OPRMASK</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### OPDMASK {#a2cf3d548b93b9e2214469a0555628464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPDMASK&nbsp;&nbsp;&nbsp;0x07ffffffLU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### OPLUS\_ {#a704503a3445b5e1cfc2ba2032f3fefc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPLUS_&nbsp;&nbsp;&nbsp;(9LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* + prefix	fwd to suffix		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### OPND {#a0eaed4c74d1e8101dbe98aa9bb336697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPND(n)&nbsp;&nbsp;&nbsp;((n)&amp;<a href="#a2cf3d548b93b9e2214469a0555628464">OPDMASK</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>.</p>

</div>
</div>

### OPRMASK {#aca404b4f6aece67469934ba024786a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPRMASK&nbsp;&nbsp;&nbsp;0xf8000000LU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>

</div>
</div>

### OPSHIFT {#ac5d1cd884391f17c78fcc188b73fe4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPSHIFT&nbsp;&nbsp;&nbsp;((unsigned)27)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ae26e3e26f2a397a734f6b8fac059b356">dofwd</a>.</p>

</div>
</div>

### OQUEST\_ {#a5fa9106fa97c3f33abc44db4f2a4f04a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OQUEST_&nbsp;&nbsp;&nbsp;(11LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* ? prefix	fwd to suffix		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### ORPAREN {#ad105523f8dbc7a2b1a0f6e98bff80ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ORPAREN&nbsp;&nbsp;&nbsp;(14LU&lt;&lt;<a href="#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>)	/* )		back to (		*/</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### OUT {#aec78e7a9e90a406a56f859ee456e8eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OUT&nbsp;&nbsp;&nbsp;(CHAR_MAX+1)	/* a non-character value */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### REGEX\_BAD {#acd206907b0132fc600321a23e82aee78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGEX_BAD&nbsp;&nbsp;&nbsp;04	/* something wrong */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a>.</p>

</div>
</div>

### SOP {#aba860196419d979bad27253aeadb088d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SOP(op, opnd)&nbsp;&nbsp;&nbsp;((<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>)|(opnd))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a>.</p>

</div>
</div>

### USEBOL {#a87eb741ccad21cee1dc3830ca3f06a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define USEBOL&nbsp;&nbsp;&nbsp;01	/* used ^ */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### USEEOL {#a79f50dd10938b851f6d38b7131e2ddd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define USEEOL&nbsp;&nbsp;&nbsp;02	/* used $ */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

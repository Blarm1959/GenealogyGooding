# Gooding evidence register

Reviewed 6 October 2026. “Export verified” below means the text was read in the GEDCOM; it does not mean the underlying historical claim was verified.

## E001 — Ancestry main-tree export

- Filename: Blarm1959.ged (also supplied as Blarm1959.zip).
- Size reviewed: 762561 bytes.
- SHA-256: `01c4ad4eb01fc68e4908c7c155a922f9c5168acc68997ce8307a01de5f06be8a`.
- Source: Bill’s existing Ancestry main tree, account Blarm1959.
- Stable saved GEDCOM identity: `libfile_78886643cc4081918759615a23e407fe`.
- Saved ZIP identity: `libfile_ce07cd6b74b88191b66aad9d0c87acea`.
- The main export spans other family branches. This package does not reproduce it in full.
- Status: export reviewed; no original certificate or record image reviewed here.

## E002 — John Wesley death-index citation

- GEDCOM individual: `@I939262738@`.
- GEDCOM source: `@S_2067573069@`.
- Source title: England & Wales, Death Index: 1916-2005.
- Ancestry collection/record identifier: `7579 / 3289323`.
- Exported record text: birth date 20 Jul 1925; death date Oct 1997; death place Barrow In Furness, Cumbria, England; birthplace blank.
- [Reconstructed record link](https://www.ancestry.co.uk/search/collections/7579/records/3289323/).
- Original exported URL: `http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsdeath93&h=3289323&ti=5538&indiv=try&gss=pt`.
- Full registration reference: not supplied in reviewed GEDCOM; obtain from record page/index.
- Assessment: useful index lead; underlying page not inspected. Birth year conflicts with tree entry. Month may be registration month; do not infer exact death date or actual death location from this text.

## E003 — John Wesley marriage-index citation

- GEDCOM individual: `@I939262738@`.
- GEDCOM source: `@S_2067014410@`.
- Source title: England & Wales, Marriage Index: 1916-2005.
- Ancestry collection/record identifier: `8753 / 27738132`.
- Exported record text: Jan-Feb-Mar 1952; Barrow-in-Furness, Cumbria.
- [Reconstructed record link](https://www.ancestry.co.uk/search/collections/8753/records/27738132/).
- Original exported URL: `http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsmarriage1984&h=27738132&ti=5538&indiv=try&gss=pt`.
- Full registration reference and spouse field: not supplied in reviewed citation text.
- Assessment: registration-quarter lead; marriage to Winifred is a tree relationship pending original entry/certificate confirmation.

## E004 — Reported parents and family-tree citations

- Clifton Auburn Gooding: `@I939468743@`; source `@S_2067596581@`, titled Ancestry Family Trees; member-tree identifier preserved as `-1355617631:1030:6051483`.
- Lorenza Vaughne: `@I28001566752@`; no individual source citation.
- John Wesley has member-tree identifiers `-1355617632:1030:6051483` and `-711448277:1030:10006801`.
- Family `@F41@` links Clifton and Lorenza with John Wesley, Frank and Una.
- Assessment: research leads only. Trees may share a common unsupported origin; multiple trees are not automatically independent corroboration.

## Exact supporting GEDCOM excerpts

These excerpts are verbatim selected records, not a standalone GEDCOM. Some pointers reference records outside the excerpt. Relationships to living people use opaque GEDCOM identifiers without reproducing their full individual records.

```text
0 @I939262738@ INDI
1 NAME John Wesley /Gooding/
2 GIVN John Wesley
2 SURN Gooding
2 SOUR @S_2067573069@
3 DATA
4 TEXT Birth date:  20 Jul 1925
5 CONT Birth place:  
5 CONT Death date:  Oct 1997
5 CONT Death place:  Barrow In Furness, Cumbria, England
4 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsdeath93&h=3289323&ti=5538&indiv=try&gss=pt
3 _APID 1,7579::3289323
2 SOUR @S_2067014410@
3 DATA
4 TEXT Marriage date:  Jan-Feb-Mar 1952
5 CONT Marriage place:  Barrow-in-Furness, Cumbria
4 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsmarriage1984&h=27738132&ti=5538&indiv=try&gss=pt
3 _APID 1,8753::27738132
1 SEX M
1 FAMC @F41@
1 FAMS @F76@
1 BIRT
2 DATE 20 07 1924
2 PLAC Bridgetown Barbados
2 SOUR @S_2067573069@
3 DATA
4 TEXT Birth date:  20 Jul 1925
5 CONT Birth place:  
5 CONT Death date:  Oct 1997
5 CONT Death place:  Barrow In Furness, Cumbria, England
4 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsdeath93&h=3289323&ti=5538&indiv=try&gss=pt
3 _APID 1,7579::3289323
1 MARR
2 DATE Jan-Feb-Mar 1952
2 PLAC Barrow-in-Furness, Cumbria
2 SOUR @S_2067014410@
3 DATA
4 TEXT Marriage date:  Jan-Feb-Mar 1952
5 CONT Marriage place:  Barrow-in-Furness, Cumbria
4 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsmarriage1984&h=27738132&ti=5538&indiv=try&gss=pt
3 _APID 1,8753::27738132
1 DEAT
2 DATE 04 Oct 1997
2 PLAC Barrow in Furness, Cumberland, Durham, Northumberland/Westmorland, Lancashire, 
2 SOUR @S_2067573069@
3 DATA
4 TEXT Birth date:  20 Jul 1925
5 CONT Birth place:  
5 CONT Death date:  Oct 1997
5 CONT Death place:  Barrow In Furness, Cumbria, England
4 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsdeath93&h=3289323&ti=5538&indiv=try&gss=pt
3 _APID 1,7579::3289323
1 SOUR @S_2067596581@
2 PAGE Ancestry Family Trees
2 _APID -1355617632:1030:6051483
2 _APID -711448277:1030:10006801
1 SOUR @S_2067573069@
2 DATA
3 TEXT Birth date:  20 Jul 1925
4 CONT Birth place:  
4 CONT Death date:  Oct 1997
4 CONT Death place:  Barrow In Furness, Cumbria, England
3 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsdeath93&h=3289323&ti=5538&indiv=try&gss=pt
2 _APID 1,7579::3289323
1 SOUR @S_2067014410@
2 DATA
3 TEXT Marriage date:  Jan-Feb-Mar 1952
4 CONT Marriage place:  Barrow-in-Furness, Cumbria
3 WWW http://search.ancestry.co.uk/cgi-bin/sse.dll?db=onsmarriage1984&h=27738132&ti=5538&indiv=try&gss=pt
2 _APID 1,8753::27738132
0 @I939264856@ INDI
1 NAME Winifred /Mansell/
2 GIVN Winifred
2 SURN Mansell
2 SOUR @S_2066641058@
3 _APID 1,8782::30340631
1 SEX F
1 FAMC @F70@
1 FAMS @F76@
1 BIRT
2 DATE 06 08 1933
2 PLAC Barrow in Furness, Cumberland, Durham, Northumberland/Westmorland, Lancashire, 
2 SOUR @S_2066641058@
3 _APID 1,8782::30340631
1 DEAT
2 DATE 26 10 2008
2 PLAC Barrow in Furness
1 SOUR @S_2067596581@
2 PAGE Ancestry Family Tree
2 _APID -711448276:1030:10006801
1 SOUR @S_2066641058@
2 _APID 1,8782::30340631
0 @I939468743@ INDI
1 NAME Clifton Auburn /Gooding/
2 GIVN Clifton Auburn
2 SURN Gooding
1 SEX M
1 FAMS @F41@
1 BIRT
2 PLAC Bridgetown, Saint Michael, Barbados
1 DEAT
2 PLAC Barbados
1 SOUR @S_2067596581@
2 PAGE Ancestry Family Trees
2 _APID -1355617631:1030:6051483
0 @I28001566752@ INDI
1 NAME Lorenza /Vaughne/
2 GIVN Lorenza
2 SURN Vaughne
1 SEX F
1 FAMS @F41@
1 BIRT
2 PLAC Bridgetown, Saint Michael, Barbados
0 @F41@ FAM
1 HUSB @I939468743@
1 WIFE @I28001566752@
1 CHIL @I939262738@
1 CHIL @I20220727167@
1 CHIL @I20220728191@
0 @F76@ FAM
1 HUSB @I939262738@
1 WIFE @I939264856@
1 CHIL @I939252568@
1 CHIL @I20215346297@
1 CHIL @I20217289733@
1 CHIL @I939556634@
1 CHIL @I939566595@
1 CHIL @I20217288746@
0 @S_2067596581@ SOUR
1 TITL Ancestry Family Trees
1 PUBL Online publication - Provo, UT, USA: Ancestry.com.  Original data:  Family Tree files submitted by Ancestry members.
1 _APID 1,1030::0
1 REPO @R_2138843261@
1 NOTE This information comes from 1 or more individual Ancestry Family Tree files. This source citation points you to a current version of those files.  Note:  The owners of these tree files may have removed or changed information since this source citat
2 CONC ion was created.
0 @S_2067573069@ SOUR
1 TITL England & Wales, Death Index: 1916-2005
1 AUTH Ancestry.com
1 PUBL Online publication - Provo, UT, USA: Ancestry.com Operations Inc, 2007.Original data - General Register Office. England and Wales Civil Registration Indexes. London, England: General Register Office. © Crown copyright. Published by permission of th
2 CONC e Contro
1 _APID 1,7579::0
1 REPO @R_2138843261@
0 @S_2067014410@ SOUR
1 TITL England & Wales, Marriage Index: 1916-2005
1 AUTH Ancestry.com
1 PUBL Online publication - Provo, UT, USA: Ancestry.com Operations, Inc, 2010.Original data - General Register Office. England and Wales Civil Registration Indexes. London, England: General Register Office. © Crown copyright. Published by permission of t
2 CONC he Contr
1 _APID 1,8753::0
1 REPO @R_2138843261@
```

## New-record entry template

- Evidence ID:
- Person/claim:
- Repository and collection:
- Exact archival/registration reference:
- Original image filename or stable link:
- Date accessed:
- Exact transcription (mark uncertain readings):
- Information supplied by / informant:
- Supports:
- Conflicts with:
- Assessment and next action:

# ICPC-COCHANGE

This repository stores our data for paper 'Do Stack Overflow Q&As and Code Co-change? An Empirical Study on Evolvement of Stack Overflow Q&As and the Impact on Code'. 

## Data on Repo level

The data we use on repository level is shown in folder 'repo'. For each repo we studied, we create a sub folder and put the data of that repo inside. For example in [ref_info.csv](repo/crate/ref_info.csv), there is detailed information (e.g., the path and line number, ID of the referred post, and the comment that includes the reference) of all references scanned from a repository. In [ref_revision.csv](repo/crate/ref_revision.csv), we store the revision count and time span of a Q&A that happens before/after the quotation. Notice that the time in our data is extracted from timestamp, which means it is in seconds. 

## Data of Stack Overflow Q&As

For the Stack Overflow Q&As, we draw the timelines and revision histories and store them in the folder 'StackOverflow'. Sub folder 'timeline' includes json files obtained using Stack Overflow API. [Post_info.json](StackOverflow/post_info.json) provides simplified information for each related post, e.g., creation and latest revision time, vote and type. [Ref_dict.json](StackOverflow/ref_dict.json) shows where are these posts quoted. 

## Issues in RQ5

In RQ5, we create issues for the repositories with code quoted from Stack Overflow that may include errors. Here is a list of the issues for which repositories that are active for the last three years. 

1. <https://github.com/veltzer/pyawskit/issues/1>
2. <https://github.com/chipmuenk/A2SRC/issues/2>
3. <https://github.com/dparks1134/biolib/issues/6>
4. <https://github.com/Scan-o-Matic/scanomatic/issues/419>
5. <https://github.com/RudolfCardinal/crate/issues/60>
6. <https://github.com/SimonGreenhill/NexusMaker/issues/2>
7. <https://github.com/oOo0oOo/BoardGameLayout/issues/1>
8. <https://github.com/FluidityProject/fluidity/issues/324>
9. <https://github.com/nrcharles/solpy/issues/5>
10. <https://github.com/varenius/salsa/issues/64>
11. <https://github.com/MarineDataTools/pymqdatastream/issues/1>
12. <https://github.com/eiriniar/CellCnn/issues/9>
13. <https://github.com/xmbcrios/xmbcrios.repository/issues/2>
14. <https://github.com/felipenaselva/felipe.repository/issues/2>
15. <https://github.com/prisms-center/CASMcode/issues/224>
16. <https://github.com/planetlabs/notebooks/issues/179>
17. <https://github.com/hectornieto/pyTSEB/issues/43>
18. <https://github.com/mwojnars/nifty/issues/7>
19. <https://github.com/Acrisel/acris/issues/1>
20. <https://github.com/siongui/pali/issues/31>
21. <https://github.com/klahnakoski/MySQL-to-S3/issues/2>
22. <https://github.com/klahnakoski/JsonSchemaToMarkdown/issues/1>
23. <https://github.com/mozilla/MoDataSubmission/issues/4>
24. <https://github.com/storiesofsolidarity/story-database/issues/9>
25. <https://github.com/joewandy/pyBatman/issues/1>
26. <https://github.com/npricejones/spectralspace/issues/2>
27. <https://github.com/edunham/toys/issues/3>
28. <https://github.com/jabbalaci/PrimCom/issues/6>
29. <https://github.com/alexsusu/icam-mobile-revival/issues/1>
30. <https://github.com/pyfa-org/Pyfa/issues/2342>
31. <https://github.com/groundcherry/bluebottle/issues/54>
32. <https://github.com/f-forcher/crystal-channeling-analysis/issues/1>
33. <https://github.com/catherinezucker/radfil/issues/35>
34. <https://github.com/jeremiedecock/snippets/issues/1>
35. <https://github.com/klahnakoski/jx-sqlite/issues/3>
36. <https://github.com/azumimuo/family-xbmc-addon/issues/1>
37. <https://github.com/chipmuenk/A2SRC/issues/2>
38. <https://github.com/klahnakoski/esReplicate/issues/2>
39. <https://github.com/maggienj/ActiveData/issues/67>
40. <https://github.com/klahnakoski/TestFailures/issues/4>
41. <https://github.com/lukasdiem/warlight2-map-generator/issues/1>
42. <https://github.com/LifeAlgorithm/VitalSourcePrinter>

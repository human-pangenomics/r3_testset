### ONT Filename Convention

```text
<run_date>_<seq_chemistry>_<kit>_<sample_id>_<flowcell>_<basecaller>_<model>_<mods>.bam
```

- **`<run_date>`**  
  Date of the run, in `MM_DD_YY` format (e.g. `11_04_24`)  
- **`<seq_chemistry>`**  
  Sequencing chemistry/version (`R9` or `R1041`)  
- **`<kit>`**  
  Library prep kit identifier (e.g. `UL` for Ultra-Long)  
- **`<sample_id>`**  
  Sample identifier (e.g. `HPRC_HG00544`)  
- **`<flowcell>`**  
  Flowcell number (`1`, `2`, etc.)  
- **`<basecaller>`**  
  Basecalling software and version (e.g. `dorado0.9.0`, `Guppy_6.5.7`)  
- **`<model>`**  
  Basecalling model name or speed (e.g. `sup5.0.0`, `450bps`)  
- **`<mods>`**  
  Modified-bases settings (e.g. `5mCG_5hmCG`, `modbases_5mc_cg_sup_prom_pass`)  

**Example R10 filename**  
```text
11_04_24_R1041_UL_HPRC_HG00544_1_dorado0.9.0_sup5.0.0_5mCG_5hmCG.bam
```
**Example R9 filename**  
```text
08_10_21_R941_HG00642_2_Guppy_6.5.7_450bps_modbases_5mc_cg_sup_prom_pass.bam
```

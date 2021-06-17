# RA2-ModuleManager-Patches
ModuleManager patches i've written for Kerbal Space Program.

---

###### ContractLimitPatch
Doubles the number of contracts shown at the Mission Control facility in career mode.  
[ContractConfigurator](https://github.com/jrossignol/ContractConfigurator/) has a difficulty settings option allowing this to be changed in-game on a per-save basis.
###### EVABuildPatch
Adds a ModuleCargoPart to parts without one, allowing them to be manipulated in EVA construction but not placed on cargo containers.  
[KSP_PartVolume](https://github.com/linuxgurugamer/KSP_PartVolume) also calculates volume for parts without a ModuleCargoPart built in, allowing them to be used inside cargo containers.
###### PodExperimentCollection
Adds functionality to manned command pods capable of experiment storage, allowing them to take experiments from other experiment containers in a vessel.
###### TankDensityPatch
Rebalances fuel tanks with densities below typical values, increasing their storage capacities to match their available internal volume better.

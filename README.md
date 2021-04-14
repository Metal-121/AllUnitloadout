# AllUnitloadout

This using SFP units and will not work with other units unless you change them inside the code. See more info inside the file.
The array file including sfp_m90w excluding the MP units.

FAQ
* How to use.

Add following to your description.ext
class Extended_Init_Eventhandlers {
	class Man {
		init = "_this call (compile preprocessFileLineNumbers 'mtl_loadout.sqf')";
	};
};

* What happens if a unit is selected in the first sorting but no loadout is found for the class

The unit will be undressed, no default option added at this time

*

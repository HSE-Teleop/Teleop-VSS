# Teleop-VSS

Repository to specify our own VSS for this project


## Todo

I think we have defined those spec files wrong. It meets our expectations, but I think the intention was different.

The root [file/s](VSS/VehicleSignalSpecification.vspec) should contain the default repository with all the general values and the overlays should extend those.

For our needs, we can keep the root file shorter than the default one, but I think it is intended to be the whole repository.

The profiles overlay is the first one applied, which adapts the values from the root file and optionally adds more if it fits the new requirements.

Then I do not know what the extensions overlay is for.
Maybe to add whole new branches with values.
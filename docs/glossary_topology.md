## [Copernicus Service Provider](../copernicus_service_provider/)
**Parents**: [Information](../information/)

## [Entity](../entity/)
**Children**: [Object](../object/), [Phenomenon](../phenomenon/), [Trait](../trait/), [User](../user/)

## [Expanded Uncertainty](../expanded_uncertainty/)
**Parents**: [Uncertainty](../uncertainty/)

## [In-situ Observation](../in-situ_observation/)
**Parents**: [Observation](../observation/), [Phenomenon](../phenomenon/), [Place](../place/), [Property](../property/), [Sensor](../sensor/), [Uncertainty](../uncertainty/)

## [Information](../information/)
**Children**: [Copernicus Service Provider](../copernicus_service_provider/), [User](../user/)

## [Location](../location/)
**Parents**: [Place](../place/)<br>
**Children**: [Representativeness](../representativeness/)

## [Measurand](../measurand/)
**Parents**: [Measurement](../measurement/), [Quantity](../quantity/)<br>
**Children**: [Uncertainty](../uncertainty/)

## [Measurement](../measurement/)
**Parents**: [Observation](../observation/), [Quantity](../quantity/)<br>
**Children**: [Measurand](../measurand/), [Representativeness](../representativeness/), [Uncertainty](../uncertainty/)

## [Object](../object/)
**Parents**: [Entity](../entity/)

## [Observation](../observation/)
**Parents**: [Phenomenon](../phenomenon/), [Property](../property/), [Sensor](../sensor/)<br>
**Children**: [In-situ Observation](../in-situ_observation/), [Measurement](../measurement/), [Reference](../reference/), [Remote Sensing](../remote_sensing/), [Representativeness](../representativeness/)

## [Period Identifier](../period_identifier/)
**Parents**: [Reference](../reference/)

## [Phenomenon](../phenomenon/)
**Parents**: [Entity](../entity/), [Property](../property/)<br>
**Children**: [In-situ Observation](../in-situ_observation/), [Observation](../observation/), [Reference](../reference/), [Remote Sensing](../remote_sensing/), [Sensor](../sensor/)

## [Place](../place/)
**Children**: [In-situ Observation](../in-situ_observation/), [Location](../location/), [Position](../position/)

## [Position](../position/)
**Parents**: [Place](../place/), [Reference](../reference/)

## [Property](../property/)
**Parents**: [Trait](../trait/)<br>
**Children**: [In-situ Observation](../in-situ_observation/), [Observation](../observation/), [Phenomenon](../phenomenon/), [Quantity](../quantity/)

## [Quantity](../quantity/)
**Parents**: [Property](../property/)<br>
**Children**: [Measurand](../measurand/), [Measurement](../measurement/)

## [Reference](../reference/)
**Parents**: [Observation](../observation/), [Phenomenon](../phenomenon/), [Uncertainty](../uncertainty/)<br>
**Children**: [Period Identifier](../period_identifier/), [Position](../position/)

## [Remote Sensing](../remote_sensing/)
**Parents**: [Observation](../observation/), [Phenomenon](../phenomenon/)

## [Representativeness](../representativeness/)
**Parents**: [Location](../location/), [Measurement](../measurement/), [Observation](../observation/)

## [Sensor](../sensor/)
**Parents**: [Phenomenon](../phenomenon/)<br>
**Children**: [In-situ Observation](../in-situ_observation/), [Observation](../observation/)

## [Standard Uncertainty](../standard_uncertainty/)
**Parents**: [Uncertainty](../uncertainty/)

## [Trait](../trait/)
**Parents**: [Entity](../entity/)<br>
**Children**: [Property](../property/)

## [Uncertainty](../uncertainty/)
**Parents**: [Measurand](../measurand/), [Measurement](../measurement/)<br>
**Children**: [Expanded Uncertainty](../expanded_uncertainty/), [In-situ Observation](../in-situ_observation/), [Reference](../reference/), [Standard Uncertainty](../standard_uncertainty/)

## [User](../user/)
**Parents**: [Entity](../entity/), [Information](../information/)


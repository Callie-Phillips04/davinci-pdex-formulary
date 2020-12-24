<table border="1"><tr><td><b>Field</b></td><td><b>Value</b></td></tr>
<tr><td>resourceType</td><td>
"List"
</td></tr>
<tr><td>meta.profile[0]</td><td>"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-CoveragePlan"</td></tr>
<tr><td>id</td><td>
"covplanV1002"
</td></tr>
<tr><td>identifier[0].value</td><td>
HIOS-PLAN-ID
</td></tr>
<tr><td>status</td><td>
"current"
</td></tr>
<tr><td>mode</td><td>
"snapshot"
</td></tr>
<tr><td>title</td><td>
"Sample Gold Health Plan"
</td></tr>
<tr><td>date</td><td>
"2015-06-12"
</td></tr>
<tr><td>entry[0].item.reference</td><td>
"MedicationKnowledge/formularydrugV1002"
</td></tr>
<tr><td>extension[0].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-DrugTierDefinition-extension"
</td></tr>
<tr><td>extension[0].extension[0].url</td><td>
"drugTierID"
</td></tr>
<tr><td>extension[0].extension[0].valueCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/CodeSystem/usdf-DrugTierCS"
</td></tr>
<tr><td>extension[0].extension[0].valueCodeableConcept.coding[0].code</td><td>
#brand
</td></tr>
<tr><td>extension[0].extension[0].valueCodeableConcept.coding[0].display</td><td>
"Brand: Brand name drugs that cost more than ‘preferred brand’ drugs."
</td></tr>
<tr><td>extension[0].extension[1].url</td><td>
"mailOrder"
</td></tr>
<tr><td>extension[0].extension[1].valueBoolean</td><td>
"false"
</td></tr>
<tr><td>extension[0].extension[2].url</td><td>
"costSharing"
</td></tr>
<tr><td>extension[0].extension[2].extension[0].url</td><td>
"pharmacyType"
</td></tr>
<tr><td>extension[0].extension[2].extension[0].valueCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/CodeSystem/usdf-PharmacyTypeCS"
</td></tr>
<tr><td>extension[0].extension[2].extension[0].valueCodeableConcept.coding[0].code</td><td>
#1-month-in-retail
</td></tr>
<tr><td>extension[0].extension[2].extension[0].valueCodeableConcept.coding[0].display</td><td>
"1 month in network retail: 1 Month Supply via in-network retail pharmacy."
</td></tr>
<tr><td>extension[0].extension[2].extension[1].url</td><td>
"copayAmount"
</td></tr>
<tr><td>extension[0].extension[2].extension[1].valueMoney.value</td><td>
20
</td></tr>
<tr><td>extension[0].extension[2].extension[2].url</td><td>
"coinsuranceRate"
</td></tr>
<tr><td>extension[0].extension[2].extension[2].valueDecimal</td><td>
"0.2"
</td></tr>
<tr><td>extension[0].extension[2].extension[3].url</td><td>
"copayOption"
</td></tr>
<tr><td>extension[0].extension[2].extension[3].valueCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/CodeSystem/usdf-CopayOptionCS"
</td></tr>
<tr><td>extension[0].extension[2].extension[3].valueCodeableConcept.coding[0].code</td><td>
#after-deductible
</td></tr>
<tr><td>extension[0].extension[2].extension[3].valueCodeableConcept.coding[0].display</td><td>
"After Deductible: The consumer first pays the deductible, and after the deductible is met, the consumer is responsible only for the copay (this indicates that this benefit is subject to the deductible)."
</td></tr>
<tr><td>extension[0].extension[2].extension[4].url</td><td>
"coinsuranceOption"
</td></tr>
<tr><td>extension[0].extension[2].extension[4].valueCodeableConcept.coding[0].system</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/CodeSystem/usdf-CoinsuranceOptionCS"
</td></tr>
<tr><td>extension[0].extension[2].extension[4].valueCodeableConcept.coding[0].code</td><td>
#after-deductible
</td></tr>
<tr><td>extension[0].extension[2].extension[4].valueCodeableConcept.coding[0].display</td><td>
"After Deductible: The consumer first pays the deductible, and after the deductible is met, the consumer pays the coinsurance portion of allowed charges (this indicates that this benefit is subject to the deductible)."
</td></tr>
<tr><td>extension[1].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-MarketingURL-extension"
</td></tr>
<tr><td>extension[1].valueString</td><td>
"http://url/to/health/plan/information"
</td></tr>
<tr><td>extension[2].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-SummaryURL-extension"
</td></tr>
<tr><td>extension[2].valueString</td><td>
"http://url/to/health/plan/information"
</td></tr>
<tr><td>extension[3].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-FormularyURL-extension"
</td></tr>
<tr><td>extension[3].valueString</td><td>
"http://url/to/formulary/information"
</td></tr>
<tr><td>extension[4].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-EmailPlanContact-extension"
</td></tr>
<tr><td>extension[4].valueString</td><td>
"email@address.com"
</td></tr>
<tr><td>extension[5].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-Network-extension"
</td></tr>
<tr><td>extension[5].valueString</td><td>
"PREFERRED"
</td></tr>
<tr><td>extension[6].url</td><td>
"http://hl7.org/fhir/us/davinci-drug-formulary/StructureDefinition/usdf-PlanIDType-extension"
</td></tr>
<tr><td>extension[6].valueString</td><td>
"HIOS-PLAN-ID"
</td></tr>
</table>
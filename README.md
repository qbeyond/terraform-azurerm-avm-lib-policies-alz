# terraform-azurerm-avm-lib-policies-alz

The QBY AVM Library supercedes the old [q.beyond Archetype Library](https://github.com/qbeyond/terraform-azurerm-archetype-lib)
that was based off the (now deprecated) [Cloud Adoption Framework](https://github.com/Azure/terraform-azurerm-caf-enterprise-scale).
It instead enriches the new [Azure Landing Zone Accelerator](https://azure.github.io/Azure-Landing-Zones/accelerator/) with useful Azure policy definitions and assignments, provided by q.beyond.

## Usage

```
provider "alz" {
  library_references = [
    {
      custom_url = "github.com/qbeyond/terraform-azurerm-avm-lib-policies-alz?ref=feature%2Finit"
    }
  ]
}
```
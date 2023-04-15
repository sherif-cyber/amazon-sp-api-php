# why fork for this package ?
package is not maintained and there's some issues needs to be fixed.

- enhance issue too many requests for amazon server (429)
> lib/Helpers/SellingPartnerApiRequest.php
- fix DateTime to string
> lib/Models/Finances/ShipmentEvent.php
> 
> change postedDate to string
- add DateTime class for finance Models.
> add DateTime class to avoid crash in package.
> 
> ClouSale\AmazonSellingPartnerAPI\Models\Finances\DateTime.


# orignial repo.
https://github.com/clousale/amazon-sp-api-php

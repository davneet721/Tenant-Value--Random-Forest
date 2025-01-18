## Summary: I define what a "valuable tenant" is, i.e., which tenants create the most value, and provide actionable insights for the client company so they can maximize profits, lower costs and increase income-stability.

## Sources of data:
* Demoraphical data provided by past tenants -- Income, rent, length of stay, pets, etc.
* Regional and property determined data -- Submarket asking rent, occupancy rates, etc.

<table>
    <thead>
        <tr>
            <th>VARIABLE</th>
            <th>DEFINITION</th>
            <th>CATEGORIZATION</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>TENANTCODE Unique</td>
            <td>identifier of a tenant</td>
            <td style="background-color: purple; color: white;">Identifier</td>
        </tr>
        <tr>
            <td>PROPERTYID Unique</td>
            <td>identifier of a property</td>
            <td style="background-color: purple; color: white;">Identifier</td>
        </tr>
        <tr>
            <td>UNITID</td>
            <td>Unique identifier of a unit</td>
            <td style="background-color: purple; color: white;">Identifier</td>
        </tr>
        <tr>
            <td>AMENITY_AMOUNT</td>
            <td>\$ Value of amenity of a unit</td>
            <td style="background-color: teal; color: white;">Value</td>
        </tr>
        <tr>
            <td>LEASETERM</td>
            <td>The length of the lease agreement in months</td>
            <td style="background-color: teal; color: white;">Value</td>
        </tr>
        <tr>
            <td>RENT</td>
            <td>Monthly rent charged</td>
            <td style="background-color: teal; color: white;">Value</td>
        </tr>
        <tr>
            <td>CONCESSION</td>
            <td>Monthly discount. The tenant's actual payment equals Rent minus Concession</td>
            <td style="background-color: teal; color: white;">Value</td>
        </tr>
        <tr>
            <td>SQFT</td>
            <td>The size of a unit</td>
            <td style="background-color: teal; color: white;">Value</td>
        </tr>
        <tr>
            <td>BEDS</td>
            <td>The number of bedrooms</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>COUNTY</td>
            <td>The location of the Essex property (Geographical Boundary)</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>REGION</td>
            <td>The location of the Essex property (Geographical Boundary)</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>SUBMARKET</td>
            <td>The location of the Essex property (Market Boundary)</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>STAR_RATING</td>
            <td>Rating of a property</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>YEAR_BUILT</td>
            <td>Property built year</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>CLOSEST_TRANSIT_STOP_DIST_MI</td>
            <td>Distance to a nearest public transit (Miles)</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>LEAD_SOURCE</td>
            <td>The source where a tenant found the Essex property</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>TYPE_OF_MOVE</td>
            <td>Where tenant moved from</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>SUB_OCCUPANCY</td>
            <td>% Units occupied in Submarket</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>SUB_PCT_CONCESSIONS_OFFER</td>
            <td>% Properties offering concession in Submarket</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>SUB_ASKING_RENT</td>
            <td>Average rent in a submarket</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>SUB_CONCESSION_ASKING_PCT</td>
            <td>\$ Concession to \$ Asking Rent in a submarket</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>PET</td>
            <td>Pet Owner</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>INDUSTRY</td>
            <td>Industry of employment</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>PRIMARY_AGE_AT_MOVE_IN</td>
            <td>Age when tenant moved-in</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>YEARLY_ADJUSTED_INCOME</td>
            <td>Annual Income of a tenant</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>TOTAL_OF_OCCUPANTS</td>
            <td>Number of Occupants</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>PCT_UNEMPLOYMENT</td>
            <td>Unemployment Rate</td>
            <td style="background-color: lightcoral;">Property (regional) Variable</td>
        </tr>
        <tr>
            <td>TOTAL_SAFETY_INDEX</td>
            <td>Safety Index of a region</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>MEDIAN_HOME_PRICE</td>
            <td>Median Home Price in the region</td>
            <td style="background-color: lightcoral;">Property Variable</td>
        </tr>
        <tr>
            <td>MOVEINYEAR</td>
            <td>Year when tenant moved-in</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>MOVEINMONTH</td>
            <td>Month when tenant moved-in</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>MOVEOUTYEAR</td>
            <td>Year when tenant moved-out (Empty if still current tenant)</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
        <tr>
            <td>MOVEOUTMONTH</td>
            <td>Month when tenant moved-out (Empty if still current tenant)</td>
            <td style="background-color: green; color: white;">Tenant Variable</td>
        </tr>
    </tbody>
</table>

## Goal to achieve with the data:
Determine which tenants are valuable
Define 'Valuable Tenant':
Profitability rate during occupancy: High payment relative to current market value of the apartment (RENT - market value of rent).

Minimize unoccupied periods: Longer times of occupancy or leasing periods.

Valuation:

The simplest model of tenant value would be to consider just the profit margin (RENT - ASKING_RENT) at the time of signing of the apartment. If we assume that the rent price updates at the rate of increase of the submarket price every new lease term, then this profit margin is constant with time and the value of a tenant will simply be a function of the duration of their stay. Thus, their value scales with the length of their occupancy.

If the tenants are locked into a RENT price when they first sign their lease, then this profit margin will change with time as the ASKING_RENT price will change for the submarket with time. In submarkets where the ASKING_RENT prices are increasing with time, the profit margin would be decreasing for the tenants that were locked into lower RENT prices with earlier MOVEIN-dates. In this case, there would be a trade-off between the profitability rate and the benefit of longer times of occupancy.

- Predict which future tenants would be valuable
Assuming the simpler model above that the profit margin at signing is maintained, then the value of a customer is determined by this initial profitability times the length of their stay. Thus, if we can predict the length of a tenant's stay from the tenant variables, we can predict how valuable they'll be.


PCA on genotypes using data from the thousand genomes project and nspired by [this paper](https://www.nature.com/articles/nature07331).

## Preview VCF on 42basepairs

* [Preview variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=variants)
* [Subsample variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=subsample&loci=22%3A16000000-16100000)


## Data files used:

```bash
# Download from 42basepairs
wget "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz"

wget "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz.tbi"

wget "https://42basepairs.com/download/s3/1000genomes/release/20110521/phase1_integrated_calls.20101123.ALL.panel"
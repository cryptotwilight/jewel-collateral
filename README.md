# Jewel Collateral
The Jewel Collateral project has been created to determine how to introduce and leverage Non-Specific Collateral (NSC) in DeFi. Non-Specific Collateral allows for the introduction of assets such as Fractional Real Estate, Digital Twins from supply chains, on chain product representations, and more to be 
resolved into a form of collateral that can be tangibly liquidated when being utilised to secure on chain debt. 

The applications of Non-Specific Collateral are wide ranging as they introduce a new form of operational finance. 
This form of operational finance can enable investors to directly finance revenues by directly financing inventory to distributors as described in the picture below:
![enter image description here](https://github.com/cryptotwilight/jewel-collateral/blob/main/media/jewel%20collateral-NSC%20Cycle.drawio.png?raw=true)

The straw man for the Jewel Collateral Mechanism is described in the diagram below: 
![enter image description here](https://github.com/cryptotwilight/jewel-collateral/blob/main/media/jewel%20collateral.drawio.png?raw=true)
In this strawman the various pools are separated logically so as to clarify their relationships to each other. The Collateral Pool has functions to support continuous valuation and emergency liquidation. The fundamental premise is that the investment pool must ALWAYS be made whole. 

The mechanism works by investors committing funds into the Investment Pool. With these funds available borrowers are able to commit Non Specific Collateral in the form of verified and valued ERC6551 tokens into  the Collateral Pool. Once the Collateral Tokens have been committed the Jewel Collateral Mechanism can now make a request to the investment pool for the issuance of a loan to the borrower via the Lending Pool. 

The Lending Pool has specific functions for loan management with the simplest being to enable the borrower to draw down against their loan and payback their loan. 

A subtle difference between Cryptocurrency Collateral and Non Specific Collateral is that when loaning against Non Specific Collateral there is a consideration of time, that is introduced to the loan as part of the risk management structure. This is different from current DeFi as loans are typically perpetual. 

# Etsy

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Etsy is a global marketplace for unique and creative handmade, vintage, and craft-supply goods. The Etsy Open API v3 is a REST + OAuth 2.0 surface that third-party developers, sellers, and integration partners use to manage shops, listings, inventory, receipts, transactions, payments, ledger entries, reviews, shipping profiles, processing profiles, production partners, return policies, and seller/buyer taxonomy. Webhooks deliver order lifecycle events (order.paid, order.canceled, order.shipped, order.delivered) to subscriber endpoints. This profile catalogs the public API surface, machine-readable artifacts, plans, rate limits, FinOps alignment, and Naftiko capabilities.

**Areas:** Marketplace · E-Commerce · Handmade · Listings · Order · Payments · Reviews · Shipping · Taxonomy · Authentication · Agentic Commerce

## Etsy on APIs.io

Everything profiled for Etsy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/etsy/](https://apis.io/providers/etsy/)** — or go straight to one of the APIs or properties below.

### APIs (28)

- [Etsy Open API v3 Webhooks](https://apis.io/apis/etsy/webhooks/) — AsyncAPI 2.6 description of Etsy's outbound webhook surface for the Open API v3. Covers the four documented event types (order.paid, order.canceled,…
- [Etsy BuyerTaxonomy API](https://apis.io/apis/etsy/etsy-buyertaxonomy-api/) — The BuyerTaxonomy API from Etsy — 2 operation(s) for buyertaxonomy.
- [Etsy Ledger Entry API](https://apis.io/apis/etsy/etsy-ledger-entry-api/) — The Ledger Entry API from Etsy — 2 operation(s) for ledger entry.
- [Etsy Other API](https://apis.io/apis/etsy/etsy-other-api/) — The Other API from Etsy — 2 operation(s) for other.
- [Etsy Payment API](https://apis.io/apis/etsy/etsy-payment-api/) — The Payment API from Etsy — 3 operation(s) for payment.
- [Etsy Review API](https://apis.io/apis/etsy/etsy-review-api/) — The Review API from Etsy — 2 operation(s) for review.
- [Etsy SellerTaxonomy API](https://apis.io/apis/etsy/etsy-sellertaxonomy-api/) — The SellerTaxonomy API from Etsy — 2 operation(s) for sellertaxonomy.
- [Etsy Shop API](https://apis.io/apis/etsy/etsy-shop-api/) — The Shop API from Etsy — 3 operation(s) for shop.
- [Etsy Shop HolidayPreferences API](https://apis.io/apis/etsy/etsy-shop-holidaypreferences-api/) — The Shop HolidayPreferences API from Etsy — 2 operation(s) for shop holidaypreferences.
- [Etsy Shop ProcessingProfiles API](https://apis.io/apis/etsy/etsy-shop-processingprofiles-api/) — The Shop ProcessingProfiles API from Etsy — 2 operation(s) for shop processingprofiles.
- [Etsy Shop ProductionPartner API](https://apis.io/apis/etsy/etsy-shop-productionpartner-api/) — The Shop ProductionPartner API from Etsy — 1 operation(s) for shop productionpartner.
- [Etsy Shop Receipt API](https://apis.io/apis/etsy/etsy-shop-receipt-api/) — The Shop Receipt API from Etsy — 3 operation(s) for shop receipt.
- [Etsy Shop Receipt Transactions API](https://apis.io/apis/etsy/etsy-shop-receipt-transactions-api/) — The Shop Receipt Transactions API from Etsy — 4 operation(s) for shop receipt transactions.
- [Etsy Shop Return Policy API](https://apis.io/apis/etsy/etsy-shop-return-policy-api/) — The Shop Return Policy API from Etsy — 3 operation(s) for shop return policy.
- [Etsy Shop Section API](https://apis.io/apis/etsy/etsy-shop-section-api/) — The Shop Section API from Etsy — 2 operation(s) for shop section.
- [Etsy Shop ShippingProfile API](https://apis.io/apis/etsy/etsy-shop-shippingprofile-api/) — The Shop ShippingProfile API from Etsy — 7 operation(s) for shop shippingprofile.
- [Etsy ShopListing API](https://apis.io/apis/etsy/etsy-shoplisting-api/) — The ShopListing API from Etsy — 13 operation(s) for shoplisting.
- [Etsy ShopListing File API](https://apis.io/apis/etsy/etsy-shoplisting-file-api/) — The ShopListing File API from Etsy — 2 operation(s) for shoplisting file.
- [Etsy ShopListing Image API](https://apis.io/apis/etsy/etsy-shoplisting-image-api/) — The ShopListing Image API from Etsy — 4 operation(s) for shoplisting image.
- [Etsy ShopListing Inventory API](https://apis.io/apis/etsy/etsy-shoplisting-inventory-api/) — The ShopListing Inventory API from Etsy — 1 operation(s) for shoplisting inventory.
- [Etsy ShopListing Offering API](https://apis.io/apis/etsy/etsy-shoplisting-offering-api/) — The ShopListing Offering API from Etsy — 1 operation(s) for shoplisting offering.
- [Etsy ShopListing Personalization API](https://apis.io/apis/etsy/etsy-shoplisting-personalization-api/) — The ShopListing Personalization API from Etsy — 2 operation(s) for shoplisting personalization.
- [Etsy ShopListing Product API](https://apis.io/apis/etsy/etsy-shoplisting-product-api/) — The ShopListing Product API from Etsy — 1 operation(s) for shoplisting product.
- [Etsy ShopListing Translation API](https://apis.io/apis/etsy/etsy-shoplisting-translation-api/) — The ShopListing Translation API from Etsy — 1 operation(s) for shoplisting translation.
- [Etsy ShopListing VariationImage API](https://apis.io/apis/etsy/etsy-shoplisting-variationimage-api/) — The ShopListing VariationImage API from Etsy — 1 operation(s) for shoplisting variationimage.
- [Etsy ShopListing Video API](https://apis.io/apis/etsy/etsy-shoplisting-video-api/) — The ShopListing Video API from Etsy — 4 operation(s) for shoplisting video.
- [Etsy User API](https://apis.io/apis/etsy/etsy-user-api/) — The User API from Etsy — 2 operation(s) for user.
- [Etsy UserAddress API](https://apis.io/apis/etsy/etsy-useraddress-api/) — The UserAddress API from Etsy — 2 operation(s) for useraddress.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (18)

Multi-step workflows that chain operations into a business task.

- [Etsy Clone an Image to a New Listing](https://apis.io/arazzos/etsy/etsy-clone-image-to-new-listing-workflow/)
- [Etsy Create Return Policy and Listing](https://apis.io/arazzos/etsy/etsy-create-return-policy-and-listing-workflow/)
- [Etsy Create Shipping Profile and Listing](https://apis.io/arazzos/etsy/etsy-create-shipping-profile-and-listing-workflow/)
- [Etsy Fulfill a Receipt](https://apis.io/arazzos/etsy/etsy-fulfill-receipt-workflow/)
- [Etsy Get My Shop Listings](https://apis.io/arazzos/etsy/etsy-get-my-shop-listings-workflow/)
- [Etsy Listing Reviews](https://apis.io/arazzos/etsy/etsy-listing-reviews-workflow/)
- [Etsy Listing with Inventory](https://apis.io/arazzos/etsy/etsy-listing-with-inventory-workflow/)
- [Etsy Organize a Listing into a Section](https://apis.io/arazzos/etsy/etsy-organize-listing-into-section-workflow/)
- [Etsy Process Unshipped Orders](https://apis.io/arazzos/etsy/etsy-process-unshipped-orders-workflow/)
- [Etsy Publish a Physical Listing](https://apis.io/arazzos/etsy/etsy-publish-physical-listing-workflow/)
- [Etsy Receipt Listings Detail](https://apis.io/arazzos/etsy/etsy-receipt-listings-detail-workflow/)
- [Etsy Receipt with Transactions](https://apis.io/arazzos/etsy/etsy-receipt-with-transactions-workflow/)
- [Etsy Reprice Listing Inventory](https://apis.io/arazzos/etsy/etsy-reprice-listing-inventory-workflow/)
- [Etsy Shop Reviews Overview](https://apis.io/arazzos/etsy/etsy-shop-reviews-overview-workflow/)
- [Etsy Shop Shipping Profiles](https://apis.io/arazzos/etsy/etsy-shop-shipping-profiles-workflow/)
- [Etsy Shop Transactions Report](https://apis.io/arazzos/etsy/etsy-shop-transactions-report-workflow/)
- [Etsy Update Shop Storefront](https://apis.io/arazzos/etsy/etsy-update-shop-storefront-workflow/)
- [Etsy User Shop Profile](https://apis.io/arazzos/etsy/etsy-user-shop-profile-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Etsy Open API v3 Webhooks](https://apis.io/asyncapis/etsy/etsy-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/etsy/webhook](https://apis.io/channels/etsy/etsy-webhook/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Etsy Agentic Access](https://apis.io/agentic-access/etsy/etsy-agentic-access/)

#### JSON Schema (86)

The data models the API reads and writes.

- [BuyerTaxonomyNode](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-node/)
- [BuyerTaxonomyNodeProperties](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-node-properties/)
- [BuyerTaxonomyNodeProperty](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-node-property/)
- [BuyerTaxonomyNodes](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-nodes/)
- [BuyerTaxonomyPropertyScale](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-property-scale/)
- [BuyerTaxonomyPropertyValue](https://apis.io/schemas/etsy/open-api-v3-buyer-taxonomy-property-value/)
- [ErrorSchema](https://apis.io/schemas/etsy/open-api-v3-error-schema/)
- [Etsy_Modules_ListingPersonalization_Api_Resources_OpenApi_ListingPersonalization](https://apis.io/schemas/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-listing-personalization/)
- [Etsy_Modules_ListingPersonalization_Api_Resources_OpenApi_PersonalizationQuestion](https://apis.io/schemas/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-personalization-question/)
- [ListingBuyerPrice](https://apis.io/schemas/etsy/open-api-v3-listing-buyer-price/)
- [ListingImage](https://apis.io/schemas/etsy/open-api-v3-listing-image/)
- [ListingImages](https://apis.io/schemas/etsy/open-api-v3-listing-images/)
- [ListingInventory](https://apis.io/schemas/etsy/open-api-v3-listing-inventory/)
- [ListingInventoryProduct](https://apis.io/schemas/etsy/open-api-v3-listing-inventory-product/)
- [ListingInventoryProductOffering](https://apis.io/schemas/etsy/open-api-v3-listing-inventory-product-offering/)
- [ListingInventoryWithAssociations](https://apis.io/schemas/etsy/open-api-v3-listing-inventory-with-associations/)
- [ListingPropertyValue](https://apis.io/schemas/etsy/open-api-v3-listing-property-value/)
- [ListingPropertyValues](https://apis.io/schemas/etsy/open-api-v3-listing-property-values/)
- [ListingReview](https://apis.io/schemas/etsy/open-api-v3-listing-review/)
- [ListingReviews](https://apis.io/schemas/etsy/open-api-v3-listing-reviews/)
- [ListingTranslation](https://apis.io/schemas/etsy/open-api-v3-listing-translation/)
- [ListingTranslations](https://apis.io/schemas/etsy/open-api-v3-listing-translations/)
- [ListingVariationImage](https://apis.io/schemas/etsy/open-api-v3-listing-variation-image/)
- [ListingVariationImages](https://apis.io/schemas/etsy/open-api-v3-listing-variation-images/)
- [ListingVideo](https://apis.io/schemas/etsy/open-api-v3-listing-video/)
- …and 61 more published on APIs.io

#### JSON Structure (86)

Data models expressed in JSON Structure.

- [Open Api V3 Buyer Taxonomy Node Properties Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-node-properties-structure/)
- [Open Api V3 Buyer Taxonomy Node Property Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-node-property-structure/)
- [Open Api V3 Buyer Taxonomy Node Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-node-structure/)
- [Open Api V3 Buyer Taxonomy Nodes Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-nodes-structure/)
- [Open Api V3 Buyer Taxonomy Property Scale Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-property-scale-structure/)
- [Open Api V3 Buyer Taxonomy Property Value Structure](https://apis.io/json-structure/etsy/open-api-v3-buyer-taxonomy-property-value-structure/)
- [Open Api V3 Error Schema Structure](https://apis.io/json-structure/etsy/open-api-v3-error-schema-structure/)
- [Open Api V3 Etsy Modules Listing Personalization Api Resources Open Api Listing Personalization Structure](https://apis.io/json-structure/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-listing-personalization-structure/)
- [Open Api V3 Etsy Modules Listing Personalization Api Resources Open Api Personalization Question Structure](https://apis.io/json-structure/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-personalization-question-structure/)
- [Open Api V3 Listing Buyer Price Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-buyer-price-structure/)
- [Open Api V3 Listing Image Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-image-structure/)
- [Open Api V3 Listing Images Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-images-structure/)
- [Open Api V3 Listing Inventory Product Offering Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-inventory-product-offering-structure/)
- [Open Api V3 Listing Inventory Product Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-inventory-product-structure/)
- [Open Api V3 Listing Inventory Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-inventory-structure/)
- [Open Api V3 Listing Inventory With Associations Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-inventory-with-associations-structure/)
- [Open Api V3 Listing Property Value Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-property-value-structure/)
- [Open Api V3 Listing Property Values Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-property-values-structure/)
- [Open Api V3 Listing Review Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-review-structure/)
- [Open Api V3 Listing Reviews Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-reviews-structure/)
- [Open Api V3 Listing Translation Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-translation-structure/)
- [Open Api V3 Listing Translations Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-translations-structure/)
- [Open Api V3 Listing Variation Image Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-variation-image-structure/)
- [Open Api V3 Listing Variation Images Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-variation-images-structure/)
- [Open Api V3 Listing Video Structure](https://apis.io/json-structure/etsy/open-api-v3-listing-video-structure/)
- …and 61 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Etsy Open Api V3 Context](https://apis.io/jsonld/etsy/etsy-open-api-v3-context/)
- [Etsy Webhooks Context](https://apis.io/jsonld/etsy/etsy-webhooks-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Etsy Vocabulary](https://apis.io/vocabularies/etsy/etsy-vocabulary/)

#### Examples (86)

Example requests and responses.

- [Open Api V3 Buyer Taxonomy Node Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-node-example/)
- [Open Api V3 Buyer Taxonomy Node Properties Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-node-properties-example/)
- [Open Api V3 Buyer Taxonomy Node Property Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-node-property-example/)
- [Open Api V3 Buyer Taxonomy Nodes Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-nodes-example/)
- [Open Api V3 Buyer Taxonomy Property Scale Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-property-scale-example/)
- [Open Api V3 Buyer Taxonomy Property Value Example](https://apis.io/examples/etsy/open-api-v3-buyer-taxonomy-property-value-example/)
- [Open Api V3 Error Schema Example](https://apis.io/examples/etsy/open-api-v3-error-schema-example/)
- [Open Api V3 Etsy Modules Listing Personalization Api Resources Open Api Listing Personalization Example](https://apis.io/examples/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-listing-personalization-example/)
- [Open Api V3 Etsy Modules Listing Personalization Api Resources Open Api Personalization Question Example](https://apis.io/examples/etsy/open-api-v3-etsy-modules-listing-personalization-api-resources-open-api-personalization-question-example/)
- [Open Api V3 Listing Buyer Price Example](https://apis.io/examples/etsy/open-api-v3-listing-buyer-price-example/)
- [Open Api V3 Listing Image Example](https://apis.io/examples/etsy/open-api-v3-listing-image-example/)
- [Open Api V3 Listing Images Example](https://apis.io/examples/etsy/open-api-v3-listing-images-example/)
- [Open Api V3 Listing Inventory Example](https://apis.io/examples/etsy/open-api-v3-listing-inventory-example/)
- [Open Api V3 Listing Inventory Product Example](https://apis.io/examples/etsy/open-api-v3-listing-inventory-product-example/)
- [Open Api V3 Listing Inventory Product Offering Example](https://apis.io/examples/etsy/open-api-v3-listing-inventory-product-offering-example/)
- [Open Api V3 Listing Inventory With Associations Example](https://apis.io/examples/etsy/open-api-v3-listing-inventory-with-associations-example/)
- [Open Api V3 Listing Property Value Example](https://apis.io/examples/etsy/open-api-v3-listing-property-value-example/)
- [Open Api V3 Listing Property Values Example](https://apis.io/examples/etsy/open-api-v3-listing-property-values-example/)
- [Open Api V3 Listing Review Example](https://apis.io/examples/etsy/open-api-v3-listing-review-example/)
- [Open Api V3 Listing Reviews Example](https://apis.io/examples/etsy/open-api-v3-listing-reviews-example/)
- [Open Api V3 Listing Translation Example](https://apis.io/examples/etsy/open-api-v3-listing-translation-example/)
- [Open Api V3 Listing Translations Example](https://apis.io/examples/etsy/open-api-v3-listing-translations-example/)
- [Open Api V3 Listing Variation Image Example](https://apis.io/examples/etsy/open-api-v3-listing-variation-image-example/)
- [Open Api V3 Listing Variation Images Example](https://apis.io/examples/etsy/open-api-v3-listing-variation-images-example/)
- [Open Api V3 Listing Video Example](https://apis.io/examples/etsy/open-api-v3-listing-video-example/)
- …and 61 more published on APIs.io

#### Collections (27)

Postman and Open Collection request collections.

- [Etsy Open API v3 BuyerTaxonomy API](https://apis.io/collections/etsy/open-etsy-buyertaxonomy-api/)
- [Etsy Open API v3 BuyerTaxonomy Ledger Entry API](https://apis.io/collections/etsy/open-etsy-ledger-entry-api/)
- [Etsy Open API v3 BuyerTaxonomy Other API](https://apis.io/collections/etsy/open-etsy-other-api/)
- [Etsy Open API v3 BuyerTaxonomy Payment API](https://apis.io/collections/etsy/open-etsy-payment-api/)
- [Etsy Open API v3 BuyerTaxonomy SellerTaxonomy API](https://apis.io/collections/etsy/open-etsy-sellertaxonomy-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop API](https://apis.io/collections/etsy/open-etsy-shop-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop HolidayPreferences API](https://apis.io/collections/etsy/open-etsy-shop-holidaypreferences-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop ProcessingProfiles API](https://apis.io/collections/etsy/open-etsy-shop-processingprofiles-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop ProductionPartner API](https://apis.io/collections/etsy/open-etsy-shop-productionpartner-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop Receipt API](https://apis.io/collections/etsy/open-etsy-shop-receipt-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop Receipt Transactions API](https://apis.io/collections/etsy/open-etsy-shop-receipt-transactions-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop Return Policy API](https://apis.io/collections/etsy/open-etsy-shop-return-policy-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop Section API](https://apis.io/collections/etsy/open-etsy-shop-section-api/)
- [Etsy Open API v3 BuyerTaxonomy Shop ShippingProfile API](https://apis.io/collections/etsy/open-etsy-shop-shippingprofile-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing API](https://apis.io/collections/etsy/open-etsy-shoplisting-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing File API](https://apis.io/collections/etsy/open-etsy-shoplisting-file-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Image API](https://apis.io/collections/etsy/open-etsy-shoplisting-image-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Inventory API](https://apis.io/collections/etsy/open-etsy-shoplisting-inventory-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Offering API](https://apis.io/collections/etsy/open-etsy-shoplisting-offering-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Personalization API](https://apis.io/collections/etsy/open-etsy-shoplisting-personalization-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Product API](https://apis.io/collections/etsy/open-etsy-shoplisting-product-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Translation API](https://apis.io/collections/etsy/open-etsy-shoplisting-translation-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing VariationImage API](https://apis.io/collections/etsy/open-etsy-shoplisting-variationimage-api/)
- [Etsy Open API v3 BuyerTaxonomy ShopListing Video API](https://apis.io/collections/etsy/open-etsy-shoplisting-video-api/)
- [Etsy Open API v3 BuyerTaxonomy User API](https://apis.io/collections/etsy/open-etsy-user-api/)
- …and 2 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Etsy — asyncapi rules](https://apis.io/rules/etsy/etsy-asyncapi-spectral-rules/)
- [Etsy — jsonschema rules](https://apis.io/rules/etsy/etsy-jsonschema-spectral-rules/)
- [Etsy API Rules](https://apis.io/rules/etsy/etsy-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Etsy Authentication](https://apis.io/security/etsy/etsy-authentication/)
- [Etsy Domain Security](https://apis.io/security/etsy/etsy-domain-security/)
- [Etsy Vulnerability Disclosure](https://apis.io/security/etsy/etsy-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Etsy Scopes](https://apis.io/scopes/etsy/etsy-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Etsy Plans Pricing](https://apis.io/plans/etsy/etsy-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Etsy Rate Limits](https://apis.io/rate-limits/etsy/etsy-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Etsy Finops](https://apis.io/finops/etsy/etsy-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.etsy.com)
- [Documentation](https://developers.etsy.com/documentation)
- [Pricing](https://developers.etsy.com/documentation/essentials/rate-limits)
- [Changelog](https://developers.etsy.com/changelog)
- [Terms of service](https://www.etsy.com/legal/api/terms)
- [Privacy policy](https://www.etsy.com/legal/privacy)
- [GitHub](https://github.com/etsy)
- [Status](https://www.etsystatus.com/)

## API Evangelist rating

**Kin Score 50.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 67.6 |
| Contract governance | 27.3 |
| Operational transparency | 36.8 |
| Developer ergonomics | 44.0 |
| Access clarity | 39.5 |

**Agent readiness 34.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 36.6** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/etsy/](https://apis.io/providers/etsy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Etsy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/etsy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

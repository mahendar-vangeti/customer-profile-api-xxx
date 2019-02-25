# customer-profile
This service offers API capabilities to be able to create and manage the profiles related to the external customers.
At the moment we support CRETAE, UPDATE & DELETE operations on a customer profile.

This service is a facade which just acts as a passthrough to the backend CRM system. Hence, most of the errors or responses are as returned by the downstream CRM interface.

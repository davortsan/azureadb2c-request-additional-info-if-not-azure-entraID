# Execute progressive profile if the user is not using Azure Entra ID to authenticate

If could be possible that you need to request additional information (progressive profile) to the user if he/she is not using Azure Entra ID identity provider, for example. In this custom policy, three identity providers were configured:
<br />
<ul>
  <li>Local account</li>
  <li>Facebook</li>
  <li>Azure Entra ID (single-account)</li>
</ul>
<br />
<b>Use case</b>
<br />
We need to request DocumentType and DocumentNumber if the user is not using Azure Entra ID for authentication.
<br />
<br />
<b>Requirements</b>
<ul>
  <li>Check that all steps of <a href="https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy">Tutorial: Create user flows and custom policies in Azure Active Directory B2C</a> were executed successfully.</li>
  <li>Add Facebook identity provider: <a href="https://learn.microsoft.com/en-us/azure/active-directory-b2c/identity-provider-facebook?pivots=b2c-custom-policy">Set up sign-up and sign-in with a Facebook account using Azure Active Directory B2C</a></li>
  <li>Add Azure Entra ID (single tenant) identity provider: <a href="https://learn.microsoft.com/en-us/azure/active-directory-b2c/identity-provider-azure-ad-single-tenant?pivots=b2c-custom-policy">Set up sign-in for a specific Microsoft Entra organization in Azure Active Directory B2C</a></li>
</ul>


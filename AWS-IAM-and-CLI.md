## IAM 

IAM stands for Identity and Access Management. It is a service offered by AWS.

<dl>
<dt> :busts_in_silhouette: This service lets you control who and what can or cannot access resources beyond AWS accounts. </dl>
</dt>

<dl>
<dt> :flags: Some of it's features : </dl>
</dl>

<dl>
<dd>- Manage users : Create and manage individual users.</dd>
<dd>- Set permissions : Define which actions a user can take within the AWS account created through permissions, this is also done through creating IAM policies that determine the resources and specify the allowed actions. Multiple policies can be attached to a individual user.</dd>
<dd>- Delegate access : IAM roles allow you to grant temporary access to resources without needing to share individual user credentials.</dd>
</dl>

___
<dl>
<dt> For me it was "not easy" to first understand the different use for IAM roles and IAM policies, finally I could find the way to difference them :</dl>
  <dd>
</dl>

<dl>
<dd>The IAM policy defines the permissions (what someone can do).</dd>
<dd>The IAM role assigns those permissions to a specific user or application (who can do it)</dd>
</dl>




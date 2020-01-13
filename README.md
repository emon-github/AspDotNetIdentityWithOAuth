# AspDotNetIdentityWithOAuth
 Asp .Net identity implementation with custom OAuth provider.

# Install the NuGet Packages:

Install-Package Microsoft.AspNet.Identity.Owin -Version 2.1.0

Install-Package Microsoft.AspNet.Identity.EntityFramework -Version 2.1.0

Install-Package Microsoft.Owin.Host.SystemWeb -Version 3.0.0

Install-Package Microsoft.AspNet.WebApi.Owin -Version 5.2.2

Install-Package Microsoft.Owin.Security.OAuth -Version 3.0.0

Install-Package Microsoft.Owin.Cors -Version 3.0.0


# Create the Database and Enable DB migrations:

enable-migrations

add-migration InitialCreate

update-database

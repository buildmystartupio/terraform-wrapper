# 4.0.1 (13/10/2017)

UPDATES :

  * TER-176 : Add license file.

# 4.0.0 (11/10/2017)

NOTES:

  * Terraform subcommands error codes are now correctly returned.
  * Terraform 0.10.x is now supported with centralized provider caching.

UPDATES:

  * TER-46 : Update requirements.txt to be compatible with Python 3.6.
  * TER-132 : Enable provider caching.
  * TER-135 : Remove unnecessary reference to role.
  * TER-139 : Return Terraform's return code.
  * TER-174 : Make sure that we pass pycodestyle check.


# 3.1.0 (13/07/2017)

NOTES:

  * Wrapper messages are now outputted to `stderr`

UPDATES:

  * TER-104 : Output wrapper messages on `stderr`
  * TER-105 : Catch some usual exceptions

# 3.0.2 (22/05/2017)

UPDATES:

  * TER-99 : Update terraform subcommands.

# 3.0.1 (10/05/2017)

NOTES:

  * This version mitigates https://github.com/hashicorp/terraform/issues/14298. For long runs, clear the cached credentials in `.run`.
  * Runs taking more than 1 hr cannot be supported from terraform `0.9.0` to at least `0.9.4`, so try to make good use of `target`.

UPDATES:

  * TER-96 : Add 15 minutes margin to AssumeRole renewal.

# 3.0.0 (27/04/2017)

NOTES:

  * Upgrade instructions : https://confluence.fr.clara.net/display/MT/Upgrade+to+Terraform+0.9

UPDATES:

  * TER-85 : Support Terraform 0.9.
  * TER-87 : Windows 10 compatibility.

# 2.0.0 (10/02/2017)

UPDATES:

  * TER-17 : Add apply confirmation.
  * TER-19 : Implement soft state locking.
  * TER-33 : Fix stack detection for global environment.
  * TER-39 : Force -update on a terraform get.
  * TER-57 : do not fail to bootstrap when bootstrap is implicit.
  * TER-59 : Support ACLs for statefiles.

# 1.1.1 (19/12/2016)

UPDATES:

  * Add default value to template.

# 1.1.0 (14/12/2016)

UPDATES:

  * TER-30 : Add support for template parameter during bootstrap.

# 1.0.0 (25/11/2016)

UPDATES:

  * TER-9 : Support wrapper execution from anywhere.

# 0.0.3 (22/08/2016)

UPDATES:

  * Fix untaint parser.

# 0.0.2 (05/08/2016)

UPDATES:

  * Bootstrap remote state before plan or apply if needed.

# 0.0.1 (05/08/2016)

  * First Release

# EPrints Import Users
EPrints plug-in for importing users from text file. This plug-in is a modified version of the [users import plug-in](http://files.eprints.org/295/) created by **Christopher Gutteridge**. Import users from a text file in the format:

`username:usertype:email:password:given_name:family_name:department:organisation`

## Usage
Use from command line import only:

`$EPRINTS_DIR/bin/import <Archive ID> user UsersOnePerLine <Text File> --verbose`

## Installation
Drop into $EPRINTS_DIR/perl_lib/EPrints/Plugin/Import


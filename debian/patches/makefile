--- a/Makefile.PL
+++ b/Makefile.PL
@@ -8,7 +8,7 @@
 auto_install();
 
 my ($lp) = ($INC{'RT.pm'} =~ /^(.*)[\\\/]/);
-my $lib_path = join( ' ', "$RT::LocalPath/lib", $lp );
+my $lib_path = $RT::PluginPath || join( ' ', "$RT::LocalPath/lib", $lp );
 my $sbin_path = $RT::SbinPath || "$RT::BasePath/sbin" || "/opt/rt3/sbin";
 my $bin_path = $RT::BinPath || "$RT::BasePath/bin" || "/opt/rt3/bin";
 

# epdfview

The URL in the old package points to http://trac.emma-soft.com/epdfview, the link is dead.

The website of the (former?) developer, Emma-Soft doesn't mention ePDFview anywhere. I have difficulty finding information about it.

http://web.archive.org/web/20120218224510/http://trac.emma-soft.com/epdfview/

Therefore we are using a fork: https://github.com/jristz/epdfview

--- a/src/gtk/MainView.cxx
+++ b/src/gtk/MainView.cxx
@@ -1192,7 +1192,7 @@ main_window_about_box_cb (GtkWidget *widget, gpointer data)
             "version", VERSION,
             "copyright", "\xc2\xa9 2006, 2007, 2009, 2010, 2011 Emma's Software",
             "license", licenseTranslated,
-            "website", "http://www.emma-soft.com/projects/epdfview/",
+            "website", "https://github.com/JotaRandom/epdfview",
             "authors", authors,
             "comments", comments,
             "translator-credits", _("translator-credits"),


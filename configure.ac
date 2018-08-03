#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
#AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AC_INIT(Mike, 2.3, mikeh@electroteach.com)
AC_CONFIG_SRCDIR([tests/oauth-test.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL

# Checks for libraries.

# Checks for header files.
AC_FUNC_ALLOCA
AC_CHECK_HEADERS([fcntl.h inttypes.h libintl.h locale.h malloc.h stddef.h stdlib.h string.h sys/time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT8_T
AC_TYPE_SIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT8_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_MKTIME
AC_FUNC_REALLOC
AC_CHECK_FUNCS([floor memset pow select setlocale sqrt strchr strcspn strrchr strstr strtol strtoul])

AC_CONFIG_FILES([copy-n-paste/Makefile
                 data/Makefile
                 data/icons/Makefile
                 data/icons/hicolor/16x16/Makefile
                 data/icons/hicolor/16x16/actions/Makefile
                 data/icons/hicolor/16x16/apps/Makefile
                 data/icons/hicolor/22x22/Makefile
                 data/icons/hicolor/22x22/actions/Makefile
                 data/icons/hicolor/22x22/apps/Makefile
                 data/icons/hicolor/24x24/Makefile
                 data/icons/hicolor/24x24/actions/Makefile
                 data/icons/hicolor/32x32/Makefile
                 data/icons/hicolor/32x32/apps/Makefile
                 data/icons/hicolor/48x48/Makefile
                 data/icons/hicolor/48x48/actions/Makefile
                 data/icons/hicolor/48x48/apps/Makefile
                 data/icons/hicolor/Makefile
                 data/icons/hicolor/scalable/Makefile
                 data/icons/hicolor/scalable/actions/Makefile
                 data/icons/hicolor/scalable/apps/Makefile
                 data/ui/Makefile
                 extensions/23hq/Makefile
                 extensions/Makefile
                 extensions/bookmarks/Makefile
                 extensions/bookmarks/data/Makefile
                 extensions/bookmarks/data/ui/Makefile
                 extensions/burn_disc/Makefile
                 extensions/burn_disc/data/Makefile
                 extensions/burn_disc/data/ui/Makefile
                 extensions/cairo_io/Makefile
                 extensions/cairo_io/data/Makefile
                 extensions/cairo_io/data/ui/Makefile
                 extensions/catalogs/Makefile
                 extensions/catalogs/data/Makefile
                 extensions/catalogs/data/ui/Makefile
                 extensions/change_date/Makefile
                 extensions/change_date/data/Makefile
                 extensions/change_date/data/ui/Makefile
                 extensions/comments/Makefile
                 extensions/comments/data/Makefile
                 extensions/comments/data/ui/Makefile
                 extensions/contact_sheet/Makefile
                 extensions/contact_sheet/data/Makefile
                 extensions/contact_sheet/data/contact_sheet_themes/Makefile
                 extensions/contact_sheet/data/ui/Makefile
                 extensions/convert_format/Makefile
                 extensions/convert_format/data/Makefile
                 extensions/convert_format/data/ui/Makefile
                 extensions/desktop_background/Makefile
                 extensions/edit_metadata/Makefile
                 extensions/edit_metadata/data/Makefile
                 extensions/edit_metadata/data/ui/Makefile
                 extensions/example/Makefile
                 extensions/example/src/Makefile
                 extensions/exiv2_tools/Makefile
                 extensions/exiv2_tools/data/Makefile
                 extensions/exiv2_tools/data/ui/Makefile
                 extensions/export_tools/Makefile
                 extensions/facebook/Makefile
                 extensions/facebook/data/Makefile
                 extensions/facebook/data/ui/Makefile
                 extensions/file_manager/Makefile
                 extensions/file_tools/Makefile
                 extensions/file_tools/data/Makefile
                 extensions/file_tools/data/ui/Makefile
                 extensions/file_viewer/Makefile
                 extensions/find_duplicates/Makefile
                 extensions/find_duplicates/data/Makefile
                 extensions/find_duplicates/data/ui/Makefile
                 extensions/flicker/Makefile
                 extensions/flicker_utils/Makefile
                 extensions/flicker_utils/data/Makefile
                 extensions/flicker_utils/data/ui/Makefile
                 extensions/gstreamer_tools/Makefile
                 extensions/gstreamer_tools/data/Makefile
                 extensions/gstreamer_tools/data/ui/Makefile
                 extensions/gstreamer_utils/Makefile
                 extensions/image_print/Makefile
                 extensions/image_print/data/Makefile
                 extensions/image_print/data/ui/Makefile
                 extensions/image_rotation/Makefile
                 extensions/image_viewer/Makefile
                 extensions/image_viewer/data/Makefile
                 extensions/image_viewer/data/ui/Makefile
                 extensions/importer/Makefile
                 extensions/importer/data/Makefile
                 extensions/importer/data/ui/Makefile
                 extensions/jpeg_utils/Makefile
                 extensions/list_tools/Makefile
                 extensions/list_tools/data/Makefile
                 extensions/list_tools/data/ui/Makefile
                 extensions/map_view/Makefile
                 extensions/oauth/Makefile
                 extensions/oauth/data/Makefile
                 extensions/oauth/data/ui/Makefile
                 extensions/photo_importer/Makefile
                 extensions/photo_importer/data/Makefile
                 extensions/photo_importer/data/ui/Makefile
                 extensions/photobucket/Makefile
                 extensions/photobucket/data/Makefile
                 extensions/photobucket/data/ui/Makefile
                 extensions/picasaweb/Makefile
                 extensions/picasaweb/data/Makefile
                 extensions/picasaweb/data/ui/Makefile
                 extensions/raw_files/Makefile
                 extensions/red_eye_removal/Makefile
                 extensions/red_eye_removal/data/Makefile
                 extensions/red_eye_removal/data/ui/Makefile
                 extensions/rename_series/Makefile
                 extensions/rename_series/data/Makefile
                 extensions/rename_series/data/ui/Makefile
                 extensions/resize_images/Makefile
                 extensions/resize_images/data/Makefile
                 extensions/resize_images/data/ui/Makefile
                 extensions/search/Makefile
                 extensions/search/data/Makefile
                 extensions/search/data/ui/Makefile
                 extensions/selections/Makefile
                 extensions/slideshow/Makefile
                 extensions/slideshow/data/Makefile
                 extensions/slideshow/data/ui/Makefile
                 extensions/webalbums/Makefile
                 extensions/webalbums/data/Makefile
                 extensions/webalbums/data/albumthemes/Classic/Makefile
                 extensions/webalbums/data/albumthemes/ClassicClips/Makefile
                 extensions/webalbums/data/albumthemes/Makefile
                 extensions/webalbums/data/albumthemes/NeatRound/Makefile
                 extensions/webalbums/data/albumthemes/Wiki/Makefile
                 extensions/webalbums/data/ui/Makefile
                 help/Makefile
                 m4/Makefile
                 pix/Makefile
                 pix/resources/Makefile
                 tests/Makefile])
AC_OUTPUT

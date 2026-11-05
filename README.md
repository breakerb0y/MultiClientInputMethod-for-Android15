# MultiClientInputMethod-for-Android15
MultiClientInputMethod for Android15

This is a Multi Client Ime implementation for Android 15.
Just copy the files to the build directories, and apply the patch where needed (you may need align it).

You also need to add this property : 
--------
    persist.debug.multi_client_ime=com.example.android.multiclientinputmethod/.MultiClientInputMethod

and add this package to the product:
--------
	PRODUCT_PACKAGES += \
    	MultiClientInputMethod

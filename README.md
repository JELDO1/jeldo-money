# hello Java API Service Starter<com.google.android.material.textfield.TextInputLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:hint="Your Ingredients">

    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/ingredientsInput"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="text"
        android:focusable="true"
        android:enabled="true"
        android:clickable="true" />
</com.google.android.material.textfield.TextInputLayout>
textveiw,icon
This is a minimal Java API service starter based on [Google Cloud Run Quickstart](https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-java-service).
<vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="24dp"
    android:height="24dp"
    android:viewportWidth="24"
    android:viewportHeight="24">
    <path
        android:fillColor="?attr/colorControlNormal"
        android:pathData="..."/>
</vector>
## Getting Startedbotton,horizontal,

Server should run automatically when starting a workspace. To run manually, run:
```sh
mvn spring-boot:run
```<com.google.android.material.textfield.TextInputLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:hint="Your Ingredients">

    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/ingredientsInput"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="text"
        android:enabled="true"Button btnSave = findViewById(R.id.btnSave);
btnSave.setOnClickListener(new View.OnClickListener() {
    @Override
    public void onClick(View v) {
        // 
        Toast.makeText(MainActivity.this, "Saving...", Toast.LENGTH_SHORT).show();

        //
        TextInputEditText input = findViewById(R.id.ingredientsInput);
        String data = input.getText().toString();

        //  (e.g Firebase, SharedPreferences, file, etc.)
    }
});
        andro    android:text="Save" />Buttod(R.id.btnSave);
btnSave.setOnClickListener(new View.OnClic    }
});
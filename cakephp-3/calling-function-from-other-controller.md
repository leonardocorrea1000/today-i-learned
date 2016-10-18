## Calling a function from another Controller

- In top of your controller:
   ```use App\Controller\MyControllerToImportController; ```

- In your function
   ```$MyControllerToImport = new MyControllerToImport();
   	  $MyControllerToImport->anotherFunction(); ```


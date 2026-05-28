<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Form</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f9f9f9; display: flex; justify-content: center; align-items: center; min-height: 100vh; margin: 0; }
        .form-container { background: #ffffff; padding: 20px; width: 100%; max-width: 500px; box-sizing: border-box; }
        .input-group { margin-bottom: 24px; }
        label { display: block; font-size: 16px; font-weight: bold; color: #333333; margin-bottom: 8px; }
        .required { color: #cc0000; margin-left: 2px; }
        input[type="text"] { width: 100%; padding: 12px 15px; font-size: 16px; border: 1.5px solid #666666; border-radius: 12px; box-sizing: border-box; outline: none; }
        input[type="text"]:focus { border-color: #000000; }
    </style>
</head>
<body>

    <div class="form-container">
        <form>
            <div class="input-group">
                <label for="education">Level of education <span class="required">*</span></label>
                <input type="text" id="education" name="education" required>
            </div>

            <div class="input-group">
                <label for="study">Field of study</label>
                <input type="text" id="study" name="study">
            </div>

            <div class="input-group">
                <label for="school">School name</label>
                <input type="text" id="school" name="school">
            </div>
        </form>
    </div>

</body>
</html>

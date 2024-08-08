<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AD-BS Date Converter Form</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/nepali-date-converter@3.3.1/dist/nepali-date-converter.umd.min.js"></script>

  <link rel="stylesheet" href="https://npmcdn.com/flatpickr/dist/flatpickr.min.css">
  <link href="nepali.datepicker.v4.0.1.min.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <form action="" method="POST">
    <div class="form-group">
      <label for="adDate">Purchase Date (A.D.):</label>
      <input type="text" id="adDate" name="adDate" class="form-control ad-date" autocomplete="off">
    </div>
    <div class="form-group">
      <label for="bsDate">Purchase Date (B.S.):</label>
      <input type="text" id="bsDate" name="bsDate" class="form-control bs-date" autocomplete="off" data-single="true">
    </div>
  </form>

  <script src="https://npmcdn.com/flatpickr"></script>
  <script src="nepali.datepicker.v4.0.1.min.js"></script>
  <script>
    document.addEventListener("DOMContentLoaded", function () {
      const adDateInput = document.getElementById('adDate');
      const bsDateInput = document.getElementById('bsDate');
      const adDatePicker = flatpickr(adDateInput, {
        locale: {
          weekDays: ["So", "Mo", "Tu", "We", "Th", "Fr", "Sa"]
        },
        dateFormat: "Y-m-d",
        onChange: (selectedDates) => {
          if (selectedDates.length > 0) {
            const adDate = selectedDates[0];
            const bsDate = new NepaliDate(adDate).getBS();
            bsDateInput.value = `${bsDate.year}-${bsDate.month + 1}-${bsDate.date}`;
            $(bsDateInput).trigger('change');

          }
        }
      });
      $('#bsDate').nepaliDatePicker({
        ndpYear: true,
        ndpMonth: true,
        onChange: (bsDate) => {
          if (bsDate && bsDate.bs) {
            const adDate = new NepaliDate(bsDate.bs).getAD();
            const adDateString = `${adDate.year}-${adDate.month+1}-${adDate.date}`;
            adDateInput.value = adDateString;
            $(adDateInput).trigger('change');
          }
        }
      });
    });
  </script>
</body>

</html>

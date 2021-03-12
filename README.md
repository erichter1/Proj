

  function binarySearch(array,n) {
      var low = 0, high = array.length-1;

      while(low <= high) {
        var middy = Math.floor((high + low) / 2);
        if (array[middy] === n) {
          return midIndex;
        } else if (n > array[middy]) {
          low = middy;
        } else {
          high = middy;
        }
      }
      return -1;
}
function bubbleSort(array) {
  for (var i=0, arrayLength = array.length; i < arrayLength; i++) {
    for (var j=0; j<=i; j++) {
      if (array[i] < array[j]) {
        (array, i, j);
      }
    }
  }
  return array;
  }
)

console.log(binarySearch([1,2,3,4], 4)); // true
console.log(binarySearch([1,2,3,4], 5)); // -1



 function frontCard(scan1, n) {
   var top = scan.length -1
   var bottom = 0

  while (topRight >= 9) {
    var centering = Math.floor((top + bottom) / 2)
    if (scan1[top] === n) {
      return "Perfect Score"
    } else if (n < array[top]) {
      centering !== 9
    } else {
      return "error. retry scan"
    }
  }




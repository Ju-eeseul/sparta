let arr = [1, 2, 3, 4];

function solution(arr) {
    var answer = 0;
    var answer = arr.reduce((a, c) => a + c) / arr.length;
    return answer;
}

let dd = solution(arr)

console.log(dd);

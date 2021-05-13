let option1 = document.getElementById('option1');
let option2 = document.getElementById('option2');
let option3 = document.getElementById('option3');
let option4 = document.getElementById('option4');
let score = document.getElementById('score');
let question = document.getElementById('image');
let reload = document.getElementById('reload');

//option 1 -------------------------------------------------------------------------
option1.addEventListener('click', ()=>{
    if(option1.textContent == 'Wales'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
        option1.style.background = 'rgb(223, 46, 46)'; //red
    },1500);

    setTimeout( ()=>{
        option1.style.borderColor = 'rgb(18, 105, 155)'; //blue
        option1.style.background = 'black';
        option1.style.color = 'ghostwhite';
        question.src = 'http://127.0.0.1:5500/questions/flags/canada.jpg';
        option1.textContent = 'USA';
        option2.textContent = 'Canada';
        option3.textContent = 'Iceland';
        option4.textContent = 'Russia';
    },2500);
}else if(option1.textContent == 'USA'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
        option1.style.background = 'rgb(223, 46, 46)'; //red
    },1500);

    setTimeout( ()=>{
        option1.style.color = 'ghostwhite';
        option1.style.background = 'black';
        question.src = 'http://127.0.0.1:5500/questions/flags/mexico.png';
        option1.textContent = 'Mexico';
        option2.textContent = 'Venezuela';
        option3.textContent = 'Spain';
        option4.textContent = 'Guatemala';
    },2500);
} else if(option1.textContent == 'Mexico'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
            option1.style.background = 'rgb(82, 236, 51)'; //green
            score.textContent++;
    },1500);

    setTimeout ( ()=>{
        option1.style.color = 'ghostwhite';
        option1.style.background = 'black';
        question.src = 'http://127.0.0.1:5500/questions/flags/greece.png';
        option1.textContent = 'Albania';
        option2.textContent = 'Bulgaria';
        option3.textContent = 'Turkey';
        option4.textContent = 'Greece';
    },2500);
}else if(option1.textContent == 'Albania'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

        setTimeout( ()=>{
            option1.style.background = 'rgb(223, 46, 46)'; //red
        },1500);
    
        setTimeout( ()=>{
            option1.style.color = 'ghostwhite';
            option1.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/newzealand.jpg';
            option1.textContent = 'Tuvalu';
            option2.textContent = 'Australia';
            option3.textContent = 'Indonesia';
            option4.textContent = 'New Zealand';
        },2500);
}else if(option1.textContent == 'Tuvalu'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
        option1.style.background = 'rgb(223, 46, 46)'; //red
    },1500);

    setTimeout( ()=>{
        option1.style.color = 'ghostwhite';
        option1.style.background = 'black';
        question.src = 'http://127.0.0.1:5500/questions/flags/slovakia.png';
        option1.textContent = 'Slovenia';
        option2.textContent = 'Slovakia';
        option3.textContent = 'Norway';
        option4.textContent = 'Serbia';
    },2500);
}else if(option1.textContent == 'Slovenia'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
        option1.style.background = 'rgb(223, 46, 46)'; //red
    },1500);

    setTimeout( ()=>{
        option1.style.color = 'ghostwhite';
        option1.style.background = 'black';
        question.src = 'http://127.0.0.1:5500/questions/flags/tunisia.jpg';
        option1.textContent = 'Tunisia';
        option2.textContent = 'Pakistan';
        option3.textContent = 'Turkey';
        option4.textContent = 'Morocco';
    },2500);
}else if(option1.textContent == 'Tunisia'){
        option1.style.background = 'yellow';
        option1.style.color = 'black';

    setTimeout( ()=>{
            option1.style.background = 'rgb(82, 236, 51)'; //green
            score.textContent++;
    },1500);

    setTimeout( ()=>{
        option1.style.color = 'ghostwhite';
        option1.style.background = 'black';
        if(score.textContent == 1){
            question.src = 'http://127.0.0.1:5500/questions/score1.png';
        }else if(score.textContent == 2){
            question.src = 'http://127.0.0.1:5500/questions/score2.png';
        }else if(score.textContent == 3){
            question.src = 'http://127.0.0.1:5500/questions/score3.png';
        }else if(score.textContent == 4){
            question.src = 'http://127.0.0.1:5500/questions/score4.png';
        }else if(score.textContent == 5){
            question.src = 'http://127.0.0.1:5500/questions/score5.png';
        }else if(score.textContent == 6){
            question.src = 'http://127.0.0.1:5500/questions/score6.png';
        }else if(score.textContent == 7){
            question.src = 'http://127.0.0.1:5500/questions/score7.png';
        }else if(score.textContent == 0){
            question.src = 'http://127.0.0.1:5500/questions/score0.png';
        };
        option1.textContent = 'Better';
        option2.textContent = 'Luck';
        option3.textContent = 'Next';
        option4.textContent = 'Time';
    },2500);
}
});
//option2----------------------------------------------------------------------------
option2.addEventListener('click', () => {

    if(option2.textContent == 'England'){
        option2.style.background = 'yellow';
        option2.style.color = 'black';

        setTimeout ( ()=>{
            option2.style.background = 'rgb(82, 236, 51)'; //green
            score.textContent++;
        },1500);

        setTimeout ( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/canada.jpg'
            option1.textContent = 'USA';
            option2.textContent = 'Canada';
            option3.textContent = 'Iceland';
            option4.textContent = 'Russia';
        },2500);
    } else if (option2.textContent == 'Canada'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

        setTimeout( ()=>{
            option2.style.background = 'rgb(82, 236, 51)'; //green
            score.textContent++;
        },1500);

        setTimeout( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/mexico.png'
            option1.textContent = 'Mexico';
            option2.textContent = 'Venezuela';
            option3.textContent = 'Spain';
            option4.textContent = 'Guatemala';
        },2500);
    } else if (option2.textContent == 'Venezuela'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

        setTimeout( ()=>{
            option2.style.background = 'rgb(223, 46, 46)'; //red
        },1500);

        setTimeout ( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/greece.png'
            option1.textContent = 'Albania';
            option2.textContent = 'Bulgaria';
            option3.textContent = 'Turkey';
            option4.textContent = 'Greece';
        },2500);
    }else if(option2.textContent == 'Bulgaria'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

        setTimeout( ()=>{
            option2.style.background = 'rgb(223, 46, 46)'; //red
        },1500);
    
        setTimeout( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/newzealand.jpg';
            option1.textContent = 'Tuvalu';
            option2.textContent = 'Australia';
            option3.textContent = 'Indonesia';
            option4.textContent = 'New Zealand';
        },2500);
    }else if(option2.textContent == 'Australia'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

        setTimeout( ()=>{
            option2.style.background = 'rgb(223, 46, 46)'; //red
        },1500);
    
        setTimeout( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/slovakia.png';
            option1.textContent = 'Slovenia';
            option2.textContent = 'Slovakia';
            option3.textContent = 'Norway';
            option4.textContent = 'Serbia';
        },2500);
}else if(option2.textContent == 'Slovakia'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

    setTimeout( ()=>{
            option2.style.background = 'rgb(82, 236, 51)'; //green
            score.textContent++;
    },1500);

    setTimeout( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/flags/tunisia.jpg';
            option1.textContent = 'Tunisia';
            option2.textContent = 'Pakistan';
            option3.textContent = 'Turkey';
            option4.textContent = 'Morocco';
    },2500);
}else if(option2.textContent == 'Pakistan'){
            option2.style.background = 'yellow';
            option2.style.color = 'black';

    setTimeout( ()=>{
            option2.style.background = 'rgb(223, 46, 46)'; //red
    },1500);

    setTimeout( ()=>{
            option2.style.color = 'ghostwhite';
            option2.style.background = 'black';
            if(score.textContent == 1){
                question.src = 'http://127.0.0.1:5500/questions/score1.png';
            }else if(score.textContent == 2){
                question.src = 'http://127.0.0.1:5500/questions/score2.png';
            }else if(score.textContent == 3){
                question.src = 'http://127.0.0.1:5500/questions/score3.png';
            }else if(score.textContent == 4){
                question.src = 'http://127.0.0.1:5500/questions/score4.png';
            }else if(score.textContent == 5){
                question.src = 'http://127.0.0.1:5500/questions/score5.png';
            }else if(score.textContent == 6){
                question.src = 'http://127.0.0.1:5500/questions/score6.png';
            }else if(score.textContent == 7){
                question.src = 'http://127.0.0.1:5500/questions/score7.png';
            }else if(score.textContent == 0){
                question.src = 'http://127.0.0.1:5500/questions/score0.png';
            };
            option1.textContent = 'Better';
            option2.textContent = 'Luck';
            option3.textContent = 'Next';
            option4.textContent = 'Time';
    },2500);
}
});
//option3 ----------------------------------------------------------------------------
option3.addEventListener('click', () => {
    if(option3.textContent == 'Scotland'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

        setTimeout ( ()=>{
            option3.style.background = 'rgb(223, 46, 46)'; //red
        },1500);

        setTimeout ( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/machu.jpg'
            option1.textContent = 'Teotihuacan';
            option2.textContent = 'Machu Picchu';
            option3.textContent = 'Nazca Lines';
            option4.textContent = 'Choquequirao';
        },2500);
    } else if (option3.textContent == 'Nazca Lines'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

        setTimeout( ()=>{
            option3.style.background = 'rgb(223, 46, 46)'; //red
            option3.style.color = 'black';
        },1500);

        setTimeout( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/brazil.jpg'
            option1.textContent = 'Argentina';
            option2.textContent = 'France';
            option3.textContent = 'Spain';
            option4.textContent = 'Brazil';
        },2500);
    } else if (option3.textContent == 'Spain'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

        setTimeout( ()=>{
            option3.style.background = 'rgb(223, 46, 46)'; //red
            option3.style.color = 'black';
        },1500);

        setTimeout ( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/salerno.jpg'
            option1.textContent = 'Salerno';
            option2.textContent = 'Barclona';
            option3.textContent = 'Zakynthos';
            option4.textContent = 'Mallorca';
        },2500);
    }else if(option3.textContent == 'Zakynthos'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

        setTimeout( ()=>{
            option3.style.background = 'rgb(223, 46, 46)'; //red
            option3.style.color = 'black';
        },1500);
    
        setTimeout( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/angkor.jpg';
            option1.textContent = 'Laos';
            option2.textContent = 'Thailand';
            option3.textContent = 'Cambodia';
            option4.textContent = 'Vietnam';
        },2500);
    }else if(option3.textContent == 'Cambodia'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

        setTimeout( ()=>{
            option3.style.background = 'rgb(82, 236, 51)'; //green
            option3.style.color = 'black';
            score.textContent++;
        },1500);
    
        setTimeout( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/rushmore.jpg';
            option1.textContent = 'South Dakota';
            option2.textContent = 'Minnesota';
            option3.textContent = 'Wisconsin';
            option4.textContent = 'Montana';
        },2500);
}else if(option3.textContent == 'Wisconsin'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

    setTimeout( ()=>{
            option3.style.background = 'rgb(223, 46, 46)'; //red
            option3.style.color = 'black';
    },1500);

    setTimeout( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/rome.jpg';
            option1.textContent = 'Milan';
            option2.textContent = 'Naples';
            option3.textContent = 'Rome';
            option4.textContent = 'Turin';
    },2500);
}else if(option3.textContent == 'Rome'){
            option3.style.background = 'yellow';
            option3.style.color = 'black';

    setTimeout( ()=>{
            option3.style.background = 'rgb(82, 236, 51)'; //green
            option3.style.color = 'black';
            score.textContent++;    
    },1500);

    setTimeout( ()=>{
            option3.style.color = 'ghostwhite';
            option3.style.background = 'black';
            if(score.textContent == 1){
                question.src = 'http://127.0.0.1:5500/questions/score1.png';
            }else if(score.textContent == 2){
                question.src = 'http://127.0.0.1:5500/questions/score2.png';
            }else if(score.textContent == 3){
                question.src = 'http://127.0.0.1:5500/questions/score3.png';
            }else if(score.textContent == 4){
                question.src = 'http://127.0.0.1:5500/questions/score4.png';
            }else if(score.textContent == 5){
                question.src = 'http://127.0.0.1:5500/questions/score5.png';
            }else if(score.textContent == 6){
                question.src = 'http://127.0.0.1:5500/questions/score6.png';
            }else if(score.textContent == 7){
                question.src = 'http://127.0.0.1:5500/questions/score7.png';
            }else if(score.textContent == 0){
                question.src = 'http://127.0.0.1:5500/questions/score0.png';
            };
            option1.textContent = 'Better';
            option2.textContent = 'Luck';
            option3.textContent = 'Next';
            option4.textContent = 'Time';
    },2500);
}
});
//option 4 ----------------------------------------------------------------------------
option4.addEventListener('click', () => {
    if(option4.textContent == 'Atlantis'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout ( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
        },1500);

        setTimeout ( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/machu.jpg'
            option1.textContent = 'Teotihuacan';
            option2.textContent = 'Machu Picchu';
            option3.textContent = 'Nazca Lines';
            option4.textContent = 'Choquequirao';
        },2500);
    } else if (option4.textContent == 'Choquequirao'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
        },1500);

        setTimeout( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/brazil.jpg'
            option1.textContent = 'Argentina';
            option2.textContent = 'France';
            option3.textContent = 'Spain';
            option4.textContent = 'Brazil';
        },2500);
    } else if (option4.textContent == 'Brazil'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout( ()=>{
            option4.style.background = 'rgb(82, 236, 51)'; //green
            option4.style.color = 'black';
            score.textContent++;
        },1500);

        setTimeout ( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/salerno.jpg'
            option1.textContent = 'Salerno';
            option2.textContent = 'Barcelona';
            option3.textContent = 'Zakynthos';
            option4.textContent = 'Mallorca';
        },2500);
    }else if(option4.textContent == 'Mallorca'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
        },1500);
    
        setTimeout( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/angkor.jpg';
            option1.textContent = 'Laos';
            option2.textContent = 'Thailand';
            option3.textContent = 'Cambodia';
            option4.textContent = 'Vietnam';
        },2500);
    }else if(option4.textContent == 'Vietnam'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
        },1500);
    
        setTimeout( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/rushmore.jpg';
            option1.textContent = 'South Dakota';
            option2.textContent = 'Minnesota';
            option3.textContent = 'Wisconsin';
            option4.textContent = 'Montana';
        },2500);
    }else if(option4.textContent == 'Montana'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

        setTimeout( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
        },1500);

        setTimeout( ()=>{
            option4.style.color = 'ghostwhite';
            option4.style.background = 'black';
            question.src = 'http://127.0.0.1:5500/questions/rome.jpg';
            option1.textContent = 'Milan';
            option2.textContent = 'Naples';
            option3.textContent = 'Rome';
            option4.textContent = 'Turin';
        },2500);
    }else if(option4.textContent == 'Turin'){
            option4.style.background = 'yellow';
            option4.style.color = 'black';

    setTimeout( ()=>{
            option4.style.background = 'rgb(223, 46, 46)'; //red
            option4.style.color = 'black';
    },1500);

    setTimeout( ()=>{
        option4.style.color = 'ghostwhite';
        option4.style.background = 'black';
        if(score.textContent == 1){
            question.src = 'http://127.0.0.1:5500/questions/score1.png';
        }else if(score.textContent == 2){
            question.src = 'http://127.0.0.1:5500/questions/score2.png';
        }else if(score.textContent == 3){
            question.src = 'http://127.0.0.1:5500/questions/score3.png';
        }else if(score.textContent == 4){
            question.src = 'http://127.0.0.1:5500/questions/score4.png';
        }else if(score.textContent == 5){
            question.src = 'http://127.0.0.1:5500/questions/score5.png';
        }else if(score.textContent == 6){
            question.src = 'http://127.0.0.1:5500/questions/score6.png';
        }else if(score.textContent == 7){
            question.src = 'http://127.0.0.1:5500/questions/score7.png';
        }else if(score.textContent == 0){
            question.src = 'http://127.0.0.1:5500/questions/score0.png';
        };
        option1.textContent = 'Better';
        option2.textContent = 'Luck';
        option3.textContent = 'Next';
        option4.textContent = 'Time';
    },2500);
}
});
// reload button -----------------------------------------------------------------------
reload.addEventListener('click',()=>{
    question.src = 'http://127.0.0.1:5500/questions/flags/england.png';
    option1.textContent = "Wales";
    option2.textContent = "England";
    option3.textContent = "Scotland";
    option4.textContent = "Ireland";
    score.textContent = 0;
});
new Vue({
            el:'#main',
            data:{
                people:['Camila','Daniela','Laura','Lina']
            },
            name:'',
            methods:{
                addName:function(){
                    this.people.push(this.name),
                    this.name = ''
                }
            }
        });